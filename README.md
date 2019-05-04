# coder
serving vs-code

**How-to-use**:  
```
docker run -it -d -p 127.0.0.1:8443:8443 \
    --restart always \
    -v "/data/coder:/home/coder/project" \
    huanghw1989/coder \
    --allow-http
```