# Docker Compose Configurations

This repository contains Docker Compose files designed to simplify deployment and management of various self-hosted applications. The initial release features a `docker-compose.yml` to set up [Apache Guacamole](https://guacamole.apache.org/), an open-source remote desktop gateway.

## Contents

- **Apache Guacamole Compose File**
  - Quickly deploy the Apache Guacamole web-based remote desktop application using containers for the frontend, backend, and supporting database.

## Getting Started

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/luckyblake02-svg/docker-stuff.git
   cd docker-stuff
   ```
   Rename the respective file to docker-compose.yml!

2. Start Apache Guacamole:
   ```bash
   docker compose up -d
   ```

   - This will pull the necessary images and start all containers defined in `docker-compose.yml`.

3. Access the Guacamole web interface:
   - Visit `http://localhost:8080/guacamole` in a browser (adjust the port if you changed it in the Compose file).

### Customization

- The Compose file can be customized to suit your environment (e.g., changing exposed ports, database credentials, or enabling SSL).

## Roadmap

- Add Docker Compose files for other self-hosted apps and services.
- Provide environment variable documentation and example configuration files.

## Contributing

Pull requests are welcome! Please submit suggestions for new Compose files or improvements.

## License

Distributed under the GPLv3 License.

***
