### Docker Compose 

[docker-compose.yml](https://github.com/yangxuan8282/ss-docker/blob/master/docker-compose/docker-compose.yml)

> default `latest` tags is for arm, and if you want to run it on amd64, please use `amd64` tags

> for shadowsocks server you have to pass `-u` arguments: 

> `ss-server -s 0.0.0.0 -p 7443 -k 1234567890 -m chacha20 -u`

> or use this docker-compose template: https://github.com/yangxuan8282/docker-recipes/blob/master/amd64/ss/docker-compose.yml 

