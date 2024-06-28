- [Qui All In One](#qui-all-in-one)
    - [Installation](#installation)
        - [Deb12Setup.sh](#deb12setup.sh)
        - [Creating DNS Records](#creating-dns-records)
            - [A Record](#a-record)
            - [CNAME Records](#cname-records)
        - [Cloning Repo](#cloning-repo)
        - [Customizing env file](#customizing-env-file)
        - [Starting Containers](#starting-containers)
        

# Qui All In One
A compose file has all the services I use.

## Installation

### Deb12Setup.sh

- If you machine doesn't have anything, you can use [Deb12Setup.sh](https://gist.github.com/thatqui/92f187bd87816cf6db0bd57db7f5a577). In reverse proxy question, don't select anything.

### Creating DNS Records

### A Record
- A @ <your ip>

### CNAME Records
- CNAME note <yourmaindomain>
- CNAME vaultwarden <yourmaindomain>

### Cloning Repo

```
git clone https://github.com/thatqui/qui-all-in-one
cd qui-all-in-one
```

### Customizing env file

- First, rename .env.template with .env

- Open .env file with editor.

- Change variables. Do not change `FLATNOTES_AUTH_TYPE`.

### Starting Containers

- Just run `docker compose up -d`
