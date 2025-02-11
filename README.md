# Servarr System - Docker Compose Setup

## 📖 Overview
This repository contains a **Docker Compose** setup for a self-hosted **Servarr** system, utilizing:
- **Radarr** (Movies)
- **Sonarr** (TV Shows)
- **Prowlarr** (Indexer Management)
- **qBittorrent** (Torrent Client)
- **Jellyfin** (Media Server)
- **Jellyseerr** (Media Requesting Server)
- **FlareSolverr** (Cloudflare Clearance Proxy)

## 📌 Features
- **Fully automated media management** 📺 🎵 📚
- **OneDrive for storage** ☁️
- **Backblaze for backups** 🔄
- **Nginx reverse proxy for secure access** 🔒
- **Optimized Docker Compose setup** 🛠️

## 🛠️ Setup Instructions
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/servarr-docker-compose.git
cd servarr-docker-compose
```

### 2️⃣ Start the Containers
```bash
docker-compose up -d
```

### 3️⃣ Access the Services
- **Radarr:** `http://localhost:7878`
- **Sonarr:** `http://localhost:8989`
- **Readarr:** `http://localhost:8787`
- **Prowlarr:** `http://localhost:9696`
- **qBittorrent:** `http://localhost:8080`
- **Jellyfin** `http://localhost:8096`
- **Jellyseerr** `http://localhost:5055`

## 🔄 Updating Services
```bash
docker-compose pull
docker-compose up -d
```

## 📝 Notes
- Ensure **Docker & Docker Compose** are installed.
- Modify `docker-compose.yml` if needed for custom setups.
- Logs can be checked with:
  ```bash
  docker-compose logs -f
  ```

## 🤝 Contributing
Feel free to open issues or submit PRs to improve the setup!

## 📬 Contact
- **Discord:** insaiyan.coder
- **Email:** [Aryan Singh](mailto:aryan@totallyinsane.tech)

