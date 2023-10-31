#### dockerfile

dockerfile is declarative way of creating images
we can build the images and we can push the images to docker repository

### how to build docker image

```
docker build -t image-name:version .
```
## how to push docker image
``````
docker login
``````
``
docker push <URL>/<username>/<image-name>:version
``