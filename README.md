
# Mailu Deployment on Coolify

## Description
This package contains the necessary files to deploy Mailu on a Coolify instance with:
- Named volumes
- Custom networks
- Docker secrets
- Health checks
- Resource limits

## Setup Instructions
1. Upload this package to your Coolify instance.
2. Ensure the `secrets/` folder contains the necessary secret files.
3. Edit the `.env` file to set non-sensitive environment variables.
4. Deploy using:
   ```bash
   docker-compose up -d
   ```

## Secrets
Place the following files in the `secrets/` directory:
- DOMAIN
- HOSTNAMES
- ADMIN
- ADMIN_PASSWORD

Each file should contain only the secret value.
