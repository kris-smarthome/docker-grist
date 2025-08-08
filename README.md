# Grist
Services:

- grist: no-code spreadsheet platform
- postgres: relational database
- redis: nosql database
- minio: S3 compatible object stire

## usage
Clone this repository to your local machine, edit the config file to match your environment, and run docker compose.

```bash
git clone https://github.com/kris-smarthome/docker-grist.git
cd docker-grist
nano .env
docker compose up -d
```

> [!NOTE]
> This stack assumes the use of Traefik, remove labels and networks if Traefik is not used. 
