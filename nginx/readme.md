# Nginx

- Set your containers to up in the same network of nginx like this:
```
networks:
    default:
      external:
        name: nginx_default
```