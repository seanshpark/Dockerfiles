## ONE-bionic

Ubuntu 18.04 based to build Samsung/ONE

### Build

```
docker build -t img_one .
```

### Run

```
docker run --name one_bionic  \
-v /home/maxwell:/home/maxwell -u $(id -u):$(id -g) \
--interactive --tty --entrypoint /bin/bash img_one
```
