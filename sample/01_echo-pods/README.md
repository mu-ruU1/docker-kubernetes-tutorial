# echo-pods

[Docker イメージ](https://hub.docker.com/r/muruu1/echo-pods)  
`muruu1/echo-pods:latest`  
`muruu1/echo-pods:v3.0`  
`muruu1/echo-pods:v2.0`  
`muruu1/echo-pods:v1.0`

リソースの再起動

```bash
kubectl rollout restart -n default deployment echo-pods
```

## 参考

- [docker-library / php](https://github.com/docker-library/php/tree/master/8.1/bullseye/apache) (GitHub)
- [php:apache-buster](https://hub.docker.com/layers/php/library/php/apache-buster/images/sha256-3116abca1a9a1314af1818fd96d3ad2e777408a1c10798fa11aa66ac88759243?context=explore) (Docker Hub)
- [PHP-FPM の Dockerfile の ENTRYPOINT や CMD を上書きしたらエラーが起きた](https://zenn.dev/flyingbarbarian/articles/bedd7961d74b83)
- [【Docker / php-fpm】docker-php-entrypoint の動作](https://qiita.com/shim-hiko/items/653059fab63af962a21f)
- [Shellscript でランダムなカラーコード生成](https://lookbackmargin.blog/2019/10/08/random-color-shellscript/)