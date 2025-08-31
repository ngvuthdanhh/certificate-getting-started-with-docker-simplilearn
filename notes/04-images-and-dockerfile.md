# 🖼️ Images and Dockerfile

## Docker Images
- Read-only templates to create containers.  
- Built in layers → efficient storage.  

## Basic Commands
- `docker images` – List images.  
- `docker pull <image>` – Download image.  
- `docker rmi <image>` – Remove image.  

## Dockerfile
- A text file with instructions to build images.  
- Example:
```dockerfile
FROM ubuntu:20.04
RUN apt-get update && apt-get install -y python3
CMD ["python3", "--version"]
```
- Build with: docker build -t myimage .
