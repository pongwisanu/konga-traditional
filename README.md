# Konga on kong with DB

## Create .env (optional)
```
echo "POSTGRES_PASSWORD=$(openssl rand -base64 36 | tr -d '\n')" >> .env
echo "KONGA_SECRET=$(openssl rand -base64 60 | tr -d '\n')" >> .env
```
