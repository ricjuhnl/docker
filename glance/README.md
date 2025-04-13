# Glance Environment Configuration

## Required Environment Variables

Before running the application, create a `.env` file in the root directory with the following configuration:

| Variable | Description |
|----------|-------------|
| `MY_SECRET_TOKEN` | Secret token for authentication |
| `IMMICH_URL` | URL for Immich service |
| `IMMICH_API_KEY` | API key for Immich service |
| `GIT_PAT_TOKEN` | GitHub Personal Access Token |
| `SONARR_URL` | URL for Sonarr service |
| `RADARR_URL` | URL for Radarr service |
| `BAZARR_URL` | URL for Bazarr service |
| `PROWLARR_URL` | URL for Prowlarr service |
| `QBIT_URL` | URL for qBittorrent service |

## Setup Instructions

1. Copy the variables above into a new file named `.env`
2. Fill in your values for each variable
3. Save the file in the same directory as your docker-compose.yml