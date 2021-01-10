# NJS Learning Materials

List some learning materials to help you step into the world of njs. Thanks to these open source authors and engineer of Nginx/F5, inc.

## Docs / Repo

- [nginx.org/en/docs/njs/](https://nginx.org/en/docs/njs/) An official nginx docs for njs.
- [github.com/nginx/njs](https://github.com/nginx/njs) An official read-only mirror of `http://hg.nginx.org/njs/` which is updated hourly.

## Example

- [xeioex/njs-examples](https://github.com/xeioex/njs-examples) Maintained by nginx,inc engineer [@Dmitry Volyntsev](https://github.com/xeioex), contains examples from official documentation. Project started at [24 Sep 2018](https://github.com/xeioex/njs-examples/commit/be03b8245fc5e6e6e8bdfabd50e1d733a87c23e2).
- [zongzw-nginx/nginx-njs-usecases](https://github.com/zongzw-nginx/nginx-njs-usecases) Maintained by F5,inc engineer [@zongzw](https://github.com/zongzw), use `docker` and `docker-compose` to demonstrate some usage scenarios of njs.Project started at [Mar 9, 2020](https://github.com/zongzw-nginx/nginx-njs-usecases/commits/master/LICENSE).

## Project

- [LDAP Auth](https://github.com/floffel/nla) by [@floffel](https://github.com/floffel)
- [S3 Proxy](https://github.com/dedok/nginx-s3) by [@Vasiliy Soshnikov](https://github.com/dedok)
- [JWT](https://github.com/lombax85/nginx-jwt) by [@lombax85](https://github.com/lombax85)
- [Mod Security](https://github.com/sreinfrasystemjp/docker-nginx-modsecurity) by [@ihironao](https://github.com/ihironao)
- [OAuth/OIDC Proxy](https://github.com/kaz/nginx-njs-oidc-proxy) by [@kaz](https://github.com/kaz)
- [NJS TypeScript Definition](https://github.com/patricknelson/nginx-njs-typescript) by [@Patrick Nelson](https://github.com/patricknelson)
- [MQTT Client Auth](https://github.com/casandberg/NGINX-mqtt-client-auth-with-SSL) by [@Chris Sandberg](https://github.com/casandberg)
- [Nginx/NJS Binares](https://github.com/jirutka/nginx-binaries) by [@Jakub Jirutka](https://github.com/jirutka)
- [Docker v2 Registry](https://github.com/psvmcc/static_docker_v2_registry) by [@Skitsanos](https://github.com/skitsanos)
- [Babel Preset](https://github.com/jirutka/babel-preset-njs) by [@Jakub Jirutka](https://github.com/jirutka)
- [OpenResty with NJS](https://github.com/skitsanos/openresty-njs) by [@Skitsanos](https://github.com/skitsanos)

## Docker Image

- [nginxinc/docker-nginx](https://github.com/nginxinc/docker-nginx) An official nginx docker images, contains njs executable files.
    - Registry: https://hub.docker.com/_/nginx
- [soulteary/docker-njs](https://github.com/soulteary/docker-njs) Maintained by soulteary, minimal image containing only njs executable files for development and debugging.
    - Registry: https://hub.docker.com/r/soulteary/docker-njs

## Alternative

> Independent project maintained by nginx fans.

- Maintained by [@Peter Leonov](https://github.com/peter-leonov) at [4 Dec 2008](https://github.com/peter-leonov/ngx_http_js_module/commit/a5e13174211f26e0b821701c972715ebd8adbb2a), full port of [ngx_http_perl_module](http://nginx.org/en/docs/http/ngx_http_perl_module.html): [peter-leonov/ngx_http_js_module](https://github.com/peter-leonov/ngx_http_js_module)
- Maintained by [@webcpp](https://github.com/webcpp) at [Apr 6, 2017](https://github.com/webcpp/hi-nginx/commit/18e478ccf4578d1136a2ea0e06f4535c7261b749#diff-a7a55a3590638a4406be827f58ad2a2b4724f42e00753b9a88d470dabf3133e9), use various languages to extend nginx as an application server: [webcpp/hi-nginx](https://github.com/webcpp/hi-nginx)
