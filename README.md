# Rocket Chat

Docker/Docker Compose codebase for Rocket Chat

### Installing

From terminal

```
mkdir rocket-chat
git clone git@github.com:RemoteCraftsmen/rocketchat.git ./rocket-chat

# prepare environment file
cp .env.example .env

# set proper data inside
nano .env

# run docker compose
docker-compose up -d --build
```

Have fun!
