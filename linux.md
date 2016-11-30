# linux

## Useful commands

### ncdu
Disk usage analyzer.

### tar
Create a new tar archive.
```bash
tar cvf archive.tar dir/
```

Extract from an existing tar archive.
```bash
tar xvf archive.tar
```

View and existing archive.
```bash
tar tvf archive.tar
```

## Docker
One liner to stop all Docker containers
```bash
docker stop $(docker ps -a -q)
```
One liner to remove all Docker containers
```bash
docker rm $(docker ps -a -q)
```