```bash
curl -sSL https://get.docker.com | sh

mkdir -p /etc/docker/containers/wg-easy/adguard/conf /etc/docker/containers/wg-easy/adguard/work

sudo curl -o /etc/docker/containers/wg-easy/docker-compose.yml https://raw.githubusercontent.com/ivaksentev/wg_adg/refs/heads/main/docker-compose.yml

cd /etc/docker/containers/wg-easy

sudo docker compose up -d

sudo docker compose ps
```
