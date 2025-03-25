# Dify部署方式

## 1. 本地部署

### 1.1 Clone Dify

Clone the Dify source code to your local machine:

```
# Assuming current latest version is 1.1.2
git clone https://github.com/langgenius/dify.git -b 1.1.2 --depth 1
```

![](images/2025-03-24_180149.png)

### 1.2 Starting Dify

Navigate to the Docker directory in the Dify source code

```
cd dify/docker
```

Copy the environment configuration file

```
cp .env.example .env
```

Start the Docker containers

Choose the appropriate command to start the containers based on the Docker Compose version on your system. 

```
docker compose up -d
```

![](images/2025-03-24_180415.png)