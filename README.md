# DinoShrimp MC

## Description

DinoShrimp MC is a SMP Minecraft server that aims to provide a seamless experience between Bedrock and Java players. The server provides Website with a small story, a 3D Web Map and a server side modding for villages and server moderation.

## Requirements

- Docker Compose
- NodeJS >= 20

## Setup

Clone the repository and go into the folder.
Then create the .env File from the .env.example:

```bash
cp .env.example .env
```

Edit the Domain Name for the website that has to point to the Server IP and add your email for the auto generated SSL certificate.


## Deploy

After you set up the project, you just can deploy it with docker-compose:

```bash
docker-compose up -d --build
```

Now the website and Minecraft Server should be running for Bedrock and Java Edition.
