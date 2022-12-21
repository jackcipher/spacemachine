# SpaceMachine
A bunch of tools builtin with free code space 4C8G machine

### How to build Skopeo

1. sudo apt update
2. sudo apt install libgpgme-dev libassuan-dev libbtrfs-dev libdevmapper-dev pkg-config
3. git clone https://github.com/containers/skopeo
4. make bin/skopeo
5. cp bin/skopeo /usr/local/bin


### Skopeo

```
skopeo --insecure copy --all docker://golang:1.19 docker://harbor.xxx.com/proxy/xxx
```
