# open-interpreter-docker

open interpreter docker environment

## Setup

Execute following command:

```sh
$ cd && git clone https://github.com/karaage0703/open-interpreter-docker
```

## Simple

### Docker build

```sh
$ cd ~/open-interpreter-docker
$ docker build -t open-interpreter-simple ./container-simple
```

### Docker run

```sh
$ cd ~/open-interpreter-docker
$ docker run -it --rm -v $(pwd):/root open-interpreter-simple
```

### Run app
Execute following command in container:

```sh
root@hostname:~# interpreter -y
```

And enjoy open interpreter


## GUI

### Docker build

```sh
$ cd ~/open-interpreter-docker
$ docker build -t open-interpreter-gui ./container-gui
```

### Docker run

```sh
$ cd ~/open-interpreter-docker
$ docker run -v $(pwd):/root -p 6080:80 open-interpreter-gui
```

### Run app

Browse http://127.0.0.1:6080/

Enjoy open interpreter


## References
- https://note.com/masia02/n/n630d091c4a02
- https://github.com/Frederic-Boulanger-UPS/docker-ubuntu_22-04-novnc
- https://rooter.jp/infra-ops/build_docker_jp_env/
