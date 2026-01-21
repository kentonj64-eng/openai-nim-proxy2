# openai-nim-proxy2
OpenAI compatible proxy for NVIDIA NIM API Select "Public"
# OpenAI-Compatible API Proxy for NVIDIA NIM (DeepSeek Models)

A simple Flask proxy that translates OpenAI API requests to NVIDIA NIM API format, specifically configured for DeepSeek models. Perfect for using with Janitor AI and other OpenAI-compatible applications.

## Features

- ✅ OpenAI-compatible API structure
- ✅ Supports DeepSeek models via NVIDIA NIM
- ✅ Easy deployment with Docker
- ✅ Janitor AI compatible
- ✅ Health checks and monitoring

## Supported Models

- `deepseek-ai/DeepSeek-Terminus-3.1`
- `deepseek-ai/DeepSeek-Coder-V2-Lite`
- `deepseek-ai/DeepSeek-V2-Lite`
- `deepseek-ai/DeepSeek-V2`
- `deepseek-ai/DeepSeek-R1`

## Quick Start

### Prerequisites

- NVIDIA API key from [NVIDIA API](https://build.nvidia.com/)
- Docker (optional)

### Using Docker (Recommended)

```bash
# Clone the repository
git clone https://github.com/yourusername/deepseek-nim-proxy.git
cd deepseek-nim-proxy

# Copy environment file
cp .env.example .env

# Edit .env with your NVIDIA API key
# NIM_API_KEY=your-actual-nvidia-api-key-here

# Run with Docker Compose
docker-compose up -d
