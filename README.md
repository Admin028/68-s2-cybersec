# 68-s2-cybersec

## 6702041510202

- Chonthicha Puengpak
- email : s6702041510202@email.kmutnb.ac.th

## Environment
cp env.example .env

## Running service

### Database

```sh
docker compose -f db.yaml up -d
docker compose -f admin.yaml up -d
docker compose -f app.yaml up -d