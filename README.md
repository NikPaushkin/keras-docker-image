# This is old version. Please, find the actual version [here](https://github.com/puzl-ee/docker-images/tree/dev/images/keras).

Keras framework based on Tensorflow 2 with various python runtime. Used by puzl.ee Kubernetes cloud.

#### Build:

```
docker build \
    --build-arg INTERPRETER=python3.8 \
    -t puzlcloud/keras:python3.8 .
```
