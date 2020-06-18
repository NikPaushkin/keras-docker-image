Keras framework based on Tensorflow 2 with various python runtime. Used by puzl.ee Kubernetes cloud.

#### Build:

```
docker build \
    --build-arg INTERPRETER=python3.8 \
    -t puzlcloud/keras:python3.8 .
```
