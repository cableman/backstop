# Backstop in Docker

```
docker pull backstopjs/backstopjs
docker run --rm -v $(pwd):/src backstopjs/backstopjs init
```

```
docker run --network="host" --rm -v $(pwd):/src backstopjs/backstopjs reference
docker run --network="host" --rm -v $(pwd):/src backstopjs/backstopjs test
open backstop_data/html_report/index.html
```