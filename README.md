Run this 

```sh
docker run -p 8080:80 -v .:/usr/share/nginx/html nginx    
```

You can then use

```sh
docker commit <name> freddy/my-site:0.1
```