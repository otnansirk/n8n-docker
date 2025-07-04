# n8n

n8n is an open-source workflow automation tool that enables you to connect various services and automate tasks using a simple, visual interface. This project is set up to run using Docker Compose for easy deployment and management.

## Features
- Visual workflow editor
- Connects to hundreds of services
- Self-hosted and extendable
- Supports custom integrations

## Prerequisites
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/)

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/otnansirk/n8n.git
   cd n8n
   ```

2. **Start the services:**
   ```bash
   docker-compose up -d
   ```

3. **Access n8n:**
   Open your browser and go to [http://localhost:5678](http://localhost:5678) (or the port specified in your `docker-compose.yml`).

## Usage
- Create and manage workflows via the web interface.
- Connect to various APIs and services.
- Automate repetitive tasks and processes.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the [Apache 2.0 License](LICENSE) (or specify your license here).