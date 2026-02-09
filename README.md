# Cyber Security

## Information
- Krittanai Srisomros (SOM)
- 6602041620033
- s6602041620033@email.kmutnb.ac.th

## Environment
```sh
cp env.example .env
```

## Running a services
### Database
```sh
docker compose -f db.yaml up #Monitoring
docker compose -f db.yaml up -d #Daemon
```

### Admin
```sh
docker compose -f admin.yaml up #monitoring
docker compose -f admin.yaml up-d #background
```

### App
```sh
docker compose -f app.yaml up #monitoring
docker compose -f app.yaml up-d #background
```
