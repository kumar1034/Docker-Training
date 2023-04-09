### DOCKER VOLUMES

Using volumes we can share the data to the containers.

`docker volume create <Volume_Names>`
`docker volume ls`
`docker volume inspect <Volume_Name>`
`docker run -d -v <host-path**:**container-path>  <Image_Name>`

## Example
```
docker run -d -v nginx_data:/usr/share/nginx/html -p 81:80 nginx
```

**-v**

**host-path:container-path**
