# open-interpreter-docker
open-interpreter docker environment


## Setup
Git clone
```sh
$ cd && git clone https://github.com/karaage0703/open-interpreter-docker
```

### Docker

#### Docker build

```sh
$ cd ~/open-interpreter-docker
$ docker build -t ubuntu:open-interpreter-docker .
```

#### Run docker

```sh
$ cd ~/open-interpreter-docker
$ docker run -it --rm -v $(pwd):/root ubuntu:open-interpreter-docker
```

#### Run app

```sh
root@hostname:~# interpreter
```

## References
- https://note.com/masia02/n/n630d091c4a02
