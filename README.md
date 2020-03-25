## Run tests

#### Local

```bash
$ bazel run //my_service:tests
```

#### Docker

```bash
$ docker run -it -v $(pwd):/my_service --entrypoint "" l.gcr.io/google/bazel:2.2.0 /bin/bash
$ cd my_service
$ bazel run //my_service:tests
```
