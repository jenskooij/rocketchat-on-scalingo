# Rocket.Chat on Scalingo
This repository deploys Rocket.Chat on Scalingo using the official Docker image.

## Required environment variables
```env
ROOT_URL=https://your-app.scalingo.io    # Your Scalingo URL
MONGO_URL=mongodb://...                  # Provisioned by MongoDb addon
PORT                                     # Provided automatically by Scalingo)
```