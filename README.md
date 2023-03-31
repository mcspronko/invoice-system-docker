# Docker for Invoice Management System

## Installation 

1. Download and install the [Docker Desktop](https://www.docker.com/products/docker-desktop/)
2. Clone the [Invoice Management System](https://github.com/mcspronko/invoice-system-docker) project repository into the `src/` directory.
```bash
cd invoice-system-docker/
git clone git@github.com:mcspronko/invoice-system.git src/
```

3. Run the composer command
```bash
cd src/
composer install 
```

4. Build docker containers
```bash
docker compose build
```

5. Build and start containers in the background 
```bash
docker-compose up -d
```

6. Stop containers
```bash
docker compose stop
```

7. Start containers
```bash
docker compose start
```