# PHP with Docker

## Getting Started

### Run the development server with Docker 🐳 :

```bash
# install pnpm
npm i -g pnpm

# run docker contaniers
docker compose -f docker-compose.dev.yml up --build

# stop and remove containers & networks
docker compose -f docker-compose.dev.yml down
```

```bash
# isntall deps
pnpm i

# cd to  /www  and run gulp
pnpm run dev

# install composer deps
composer install

```
