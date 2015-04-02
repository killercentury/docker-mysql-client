# MySQL Client Docker Image

This image is based on the offical [Alpine Docker image](https://registry.hub.docker.com/_/alpine/). It should provide you the smallest MySQL Client.

Run command like this to connect to your MySQL:
```
docker run -it --rm killercentury/mysql-client -h YOUR_HOST -u YOUR_USER -p
```
