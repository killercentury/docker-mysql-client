# MySQL Client Docker Image

This image is based on the offical [Alpine Docker image](https://registry.hub.docker.com/_/alpine/). It should provide the smallest MySQL client.

## Usage

```
docker run -it --rm killercentury/mysql-client -h YOUR_HOST -u YOUR_USER -p
```

Above command only represents the most common use case, please refer to the offical MySQL documentation for using other parameters.
