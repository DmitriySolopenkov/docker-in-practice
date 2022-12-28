## id containers
```bash
docker ps -a -q
```
## Remove all containers

```bash
docker rm $(docker ps -a -q)
```

## Remove all images

```bash
docker rmi $(docker images -q)
```