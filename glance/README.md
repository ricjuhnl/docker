# Glance Environment Configuration

## Required Environment Variables

Before running the application, create a `.env` file in the root directory with the following configuration:

```shell
MY_SECRET_TOKEN=
IMMICH_URL=
IMMICH_API_KEY=
GIT_PAT_TOKEN=
SONARR_URL=
RADARR_URL=
BAZARR_URL=
PROWLARR_URL=
QBIT_URL=
ALPINE_URL=
JELLYFIN_URL=
PROXMOXVE_URL=
PROXMOXVE_KEY=
```

## Setup Instructions

1. Copy the variables above into a new `.env` file
2. Fill in your values for each variable
3. Save the file in the same directory as your docker-compose.yml
