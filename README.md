### My favorite containers in one Docker Compose stack.

- Cloning repository.

```sh
git clone https://github.com/dkroderos/containers
cd containers
```

- Generate `.env` file the using `.env.example` file.

```sh
cp .env.example .env # On Linux
```

```sh
Copy-Item .env.example .env # On Windows
```

- Running the containers.

```sh
docker compose up -d
```
