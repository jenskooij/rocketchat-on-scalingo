# Rocket.Chat on Scalingo
This repository deploys Rocket.Chat on Scalingo using the official Docker image.

[![Deploy on Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://my.scalingo.com/deploy?source=https://gitlab.com/yecco-oss/rocket.chat-on-scalingo#master)

## Required environment variables
```env
ROOT_URL=https://your-app.scalingo.io    # Your Scalingo URL
MONGO_URL=mongodb://...                  # Provisioned by MongoDb addon
PORT                                     # Provided automatically by Scalingo)
```