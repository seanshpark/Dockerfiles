## ONE-focal

Ubuntu 20.04 based to build Samsung/ONE

### Build

```
docker build -t img_one_focal .
```

### Run

```
docker run --name one_focal  \
-v /home/maxwell:/home/maxwell -u $(id -u):$(id -g) \
--interactive --tty --entrypoint /bin/bash img_one_focal
```
