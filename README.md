# docker-rabbitmq

Docker image with following plugins enabled:
- `rabbitmq_consistent_hash_exchange `
- `rabbitmq_event_exchange`
- `rabbitmq_federation`
- `rabbitmq_federation_management`
- `rabbitmq_management`
- `rabbitmq_management_agent`
- `rabbitmq_shovel`
- `rabbitmq_shovel_management`
- `rabbitmq_web_dispatch`

## Build

```shell
docker build -t custom-rabbitmq:latest .
```
