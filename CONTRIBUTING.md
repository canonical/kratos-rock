# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:kratos_amd64.rock docker-daemon:kratos:latest
docker run kratos:latest
```
