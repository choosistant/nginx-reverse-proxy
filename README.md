# nginx Reverse Proxy

```bash
docker run \
    --name nginx-choosistant \
    -p 9999:80 \
    -v $(pwd)/default.conf:/etc/nginx/conf.d/default.conf:ro \
    --rm \
    nginx:latest
```
