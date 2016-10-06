# Virtualmin Docker image

Virtualmin installation on CentOS 6.

```shell
docker run --rm -it --name virtualmin -v "/tmp/backup:/backup" --net host cloudinovasi/virtualmin
```

Default credentials are `root` / `admin`.
