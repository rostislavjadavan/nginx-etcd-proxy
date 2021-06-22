# ⚗️ nginx etcd proxy

Simple proxy for etcd listening on port 2377 using docker and official nginx docker image.

To specify etcd host create `.env` file with following content:

```
ETCD_HOST=https://etcd.host
```

Then run:

```
docker-compose up
```