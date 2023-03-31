# Docker for Invoice Management System

## Installation 

1. Download and install the [Docker Desktop](https://www.docker.com/products/docker-desktop/)
2. Clone current repository
```bash
git clone git@github.com:mcspronko/invoice-system-docker.git
```

3. Clone the [Invoice Management System](https://github.com/mcspronko/invoice-system-docker) project repository into the `src/` directory.
```bash
cd invoice-system-docker/
git clone git@github.com:mcspronko/invoice-system.git src/
```

4. Run the composer command
```bash
cd src/
composer install 
```

5. Build and start containers in the background 
```bash
docker compose up -d
```

Navigate to the http://localhost in a browser.

### Additional Docker commands

1. Stop containers
```bash
docker compose stop
```

2. Start containers
```bash
docker compose start
```

3. Delete containers
```bash
docker compose down 
```
