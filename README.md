# Simplest Reverse Proxy Ever

This app has two Flask apps (as container) and a NGINX. We compose all of them using a docker compose script to demonstrate a simplest example of reverse proxy.

To run the servers:

```bash
docker-compose up
```

Test the apps by:

```bash
curl http://0.0.0.0/app1
curl http://0.0.0.0/app2
```
