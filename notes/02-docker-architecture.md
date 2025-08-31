# ⚙️ Docker Architecture

## Core Components
- **Docker Engine**: Core runtime to build and run containers.  
- **Docker Daemon (`dockerd`)**: Runs in the background, manages images & containers.  
- **Docker CLI**: Command-line interface to interact with Docker.  
- **Docker Registry**: Stores and distributes images (default: Docker Hub).  

## Workflow
1. User runs a Docker CLI command.  
2. CLI communicates with Docker Daemon.  
3. Daemon pulls/builds image and runs container.  

