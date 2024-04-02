# rabbitmq-management-shovel
Adds shovel to the management rabbitmq image

To Build multiarch, run the following command (assuming you're building from 3.13.0 in your Dockerfile):
```
docker buildx build --platform linux/amd64,linux/arm64 -t dsmithson/rabbitmq-management-shovel:latest -t dsmithson/rabbitmq-management-shovel:3.13.0 --push .
```

