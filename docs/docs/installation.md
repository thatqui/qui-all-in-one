# Installation

## Deb12Setup.sh

If your machine doesn't have anything, you can use [Deb12Setup.sh](https://gist.github.com/thatqui/92f187bd87816cf6db7f5a577). In reverse proxy question, don't select anything.

## DNS Records

### A Record
- `A @ [yourip]`

### CNAME Records
- `CNAME fn [yourdomain]`
- `CNAME bw [yourdomain]`
- `CNAME lr [yourdomain]`
- `CNAME fr [yourdomain]`

## Cloning Repo

```
git clone https://github.com/thatqui/qui-all-in-one.git
cd qui-all-in-one
```

## Customize .env file

- Copy .env.template file: `cp .env.template .env`
- Customize .env file.

## Starting Containers

- Just run `docker compose up -d` or `docker-compose up -d`. 
