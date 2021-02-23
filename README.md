# graphql-server-example

This is a demo for display graphql with dataloader and authentication build on koa

## Prerequisites
- [docker](https://www.docker.com/products/docker-desktop)
- [docker-compose](https://docs.docker.com/compose/install/)

## Usage
start app and mysql service up
```bash
$ docker-compose up -d
```
and then open browser with url: localhost:3000/graphql

![list payment](https://github.com/GrassShrimp/graphql-server-example/blob/master/list_payment.jpg)

![delete payment failure](https://github.com/GrassShrimp/graphql-server-example/blob/master/delete_payment_failure.jpg)

![user login](https://github.com/GrassShrimp/graphql-server-example/blob/master/user_login.jpg)

![delete payment successful](https://github.com/GrassShrimp/graphql-server-example/blob/master/delete_payment_successful.jpg)