# llama-mlx-pipeline

A Local-First Data Extraction Pipeline powered by Apple MLX

## Installation

```bash
pip install -e .
```

## Usage

```python
from llama_mlx_pipeline import LlamaMlxPipelineClient

# Initialize the client
client = LlamaMlxPipelineClient(api_key="your-api-key")
result = client.query("your query")
print(result)
```

## Features

- Fast and efficient
- Easy to use API
- Comprehensive documentation

## Development

### Setup

```bash
# Clone the repository
git clone https://github.com/nikjois/llama-mlx-pipeline.git
cd llama-mlx-pipeline

# Install development dependencies
pip install -e ".[dev]"
```

### Testing

```bash
pytest
```

## License

MIT

## Author

Nik Jois (nikjois@llamasearch.ai)
