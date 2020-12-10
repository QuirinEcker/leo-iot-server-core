# iotservercore
This is repository holds the docker-compose file and whole config for iotserver

## Deployment
### Git tag

When a new feature is applied add a git Tag

```bash
git tag -a v0.0.0 -m "my release notes"
git push origin v0.0.0
```

### Download
```bash
git clone github.com/andileeb/iotservercore
```

### Update
```bash
git pull
```

### Start

```bash
docker-compose up
```

### Stop
```bash
docker-compose stop
```

### Logs
```bash
docker-compose logs
```

### Update a running system
```bash
docker-compose stop
git pull
docker-compose up
```
