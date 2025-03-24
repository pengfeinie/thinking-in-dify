







### Clone Dify

Clone the Dify source code to your local machine:

```
# Assuming current latest version is 1.1.2
git clone https://github.com/langgenius/dify.git -b 1.1.2 --depth 1
```

### Starting Dify

Navigate to the Docker directory in the Dify source code

```
cd dify/docker
```

Copy the environment configuration file

```
cp .env.example .env
```

Start the Docker containers

Choose the appropriate command to start the containers based on the Docker Compose version on your system. You can use the `$ docker compose version` command to check the version, and refer to the [Docker documentation](https://docs.docker.com/compose/install/) for more information:

- If you have Docker Compose V2, use the following command:

Copy

```
docker compose up -d
```

- If you have Docker Compose V1, use the following command:

Copy

```
docker-compose up -d
```