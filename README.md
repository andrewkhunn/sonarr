### [Sonarr](https://github.com/Sonarr/Sonarr)

```shell
docker run --rm --name sonarr -p 8989:8989 -v /tmp/sonarr:/config hotio/sonarr
```

```yaml
sonarr:
  container_name: sonarr
  image: hotio/sonarr
  ports:
    - "8989:8989"
  volumes:
    - /tmp/sonarr:/config
```

```shell
VERSION=image
VERSION=stable
VERSION=unstable
VERSION=v3
VERSION=https://download.sonarr.tv/v2/master/mono/NzbDrone.master.2.0.0.5228.mono.tar.gz
VERSION=file:///config/NzbDrone.master.2.0.0.5228.mono.tar.gz
```
