## 👋 Welcome to umbrel 🚀

Personal server OS for self-hosting

## 📋 Description

Personal server OS for self-hosting

## 🚀 Services

- **app**: dockurr/umbrel:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/umbrel/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/umbrel" ~/.local/srv/docker/umbrel
cd ~/.local/srv/docker/umbrel
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install umbrel
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:59081

## 📂 Volumes

- `./volumes/data/umbrel` - Data storage

## 🔍 Logging

```shell
docker compose logs -f app
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
