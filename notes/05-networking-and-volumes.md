# 🌐 Networking and Volumes

## Networking
- **Bridge** (default): Containers communicate on same host.  
- **Host**: Shares host’s network namespace.  
- **Overlay**: For multi-host communication.  

Commands:
- `docker network ls`  
- `docker network create mynet`  
- `docker network connect mynet <container>`  

## Volumes
- Persistent data beyond container lifecycle.  
- `docker volume create mydata`  
- Mount: `docker run -v mydata:/app/data myimage`  
