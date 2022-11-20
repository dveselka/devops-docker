## HOWTO

* https://developers.redhat.com/articles/2021/11/30/build-lightweight-and-secure-container-images-using-rhel-ubi#
* https://danielveselka.blogspot.com/2022/10/docker-ubi-redhat-image.html

### Compile Docker image

```
docker build -t redhat-ubi-myapp .
```

### Run container 
```
docker run redhat-ubi-myapp
```
