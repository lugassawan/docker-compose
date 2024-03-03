# Rabbit MQ

## How To

- Download plugin, e.g. rabbitmq_delayed_message_exchange

```bash
wget https://github.com/rabbitmq/rabbitmq-delayed-message-exchange/releases/download/v3.12.0/rabbitmq_delayed_message_exchange-3.12.0.ez -P ./plugins/
```

- Add into `enabled_plugins` file

```
[rabbitmq_management,rabbitmq_prometheus,rabbitmq_delayed_message_exchange].
```

- Run `docker-compose up -d` to apply the plugins

## Plugins

| Plugin                            | Built-In | Source                                                                |
| --------------------------------- | -------- | --------------------------------------------------------------------- |
| rabbitmq_shovel                   | `Yes`    | -                                                                     |
| rabbitmq_shovel_management        | `Yes`    | -                                                                     |
| rabbitmq_delayed_message_exchange | `No`     | [Link](https://github.com/rabbitmq/rabbitmq-delayed-message-exchange) |
