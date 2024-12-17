# Gallium Engine

A professional-grade audio workstation with real-time processing capabilities.

## Features

- Real-time audio processing with JACK integration
- Containerized deployment for consistent environments
- Modern UI built with Qt6
- Comprehensive audio routing and MIDI support

## Project Structure

```
/audio-workstation/
├── docker/         # Container and deployment configurations
├── src/           # Source code and core components
├── assets/        # Media and resource files
├── scripts/       # Build and utility scripts
├── docs/          # Documentation and guides
└── tests/         # Test suites and benchmarks
```

## Getting Started

### Prerequisites

- Docker & Docker Compose
- JACK Audio Connection Kit
- Qt6 development tools
- C++ compiler and build tools

### Quick Start

1. Clone the repository
2. Build the Docker image
3. Start the container

```bash
git clone https://github.com/ShawnJosephSLU/Gallium-Engine.git
cd Gallium-Engine
docker-compose up --build
```

## Development

See the [Development Guide](docs/development/README.md) for detailed setup instructions.

## Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md) for details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.