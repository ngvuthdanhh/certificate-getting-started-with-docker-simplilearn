# 📑 Docker Compose

## What is Docker Compose?
- Tool for defining and running **multi-container apps** using YAML.  

## Example `docker-compose.yml`
```yaml
version: "3"
services:
  web:
    image: nginx
    ports:
      - "8080:80"
  db:
    image: mysql
    environment:
      MYSQL_ROOT_PASSWORD: example
```
## Commands

- docker-compose up – Start services.

- docker-compose down – Stop and remove services.

- docker-compose ps – List services.
