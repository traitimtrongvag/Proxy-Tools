# Proxy Tool

A Python-based tool for collecting and filtering public proxies to ensure anonymity and security while browsing.

## Features

### Get Proxy
- Automatically collects proxies from public sources
- Saves proxy list to `Andeptrai.txt`
- Supports HTTP, HTTPS, and SOCKS proxies
- Format: `IP:PORT` (one per line)

### Filter Proxy
- Removes unsafe and unstable proxies
- Checks:
  - **Security**: HTTPS support verification
  - **Speed**: Response time testing
  - **Availability**: Connection stability
- Keeps only high-quality, reliable proxies

## Benefits

- **Anonymity**: Browse without tracking
- **Privacy**: Protect personal information
- **Access**: Bypass geo-restrictions

## Usage

1. **Collect proxies**: Run get proxy to save list to `Andeptrai.txt`
2. **Filter proxies**: Run filter proxy to keep quality proxies only

## Requirements

- Python 3.x
- Required libraries (see `requirements.txt`)

## Installation

```bash
pip install -r requirements.txt
```

## License

MIT