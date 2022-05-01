# minio_docker_nginx
## first of all we create docker-compose
### vim /root/docker-compose.yml
## after that we must create nginx config to expose minio service
### vim /etc/nginx/conf.d/minio.k8s.yourdomain.conf

## minio urls: 

```
consol url: https://consol-minio.example.com/ 

api url: https://api-minio.example.com/ 
```
