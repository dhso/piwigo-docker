# piwigo-docker

> piwigo for docker.

## 运行 run
```bash
docker run -d \
--name piwigo \
--restart=always \
-p 5080:80 \
-v piwigo_pictures:/pictures \
-v piwigo_galleries:/galleries \
dhso/piwigo:latest
```

## 编译
```bash
docker build -t dhso/piwigo .
```