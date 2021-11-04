# READEME

here is website app dir.

you can use docker add app.

# pull sscms:latest
```
docker pull sscms/core:latest
```

### docker shell
``` docker (windows)
docker run -d --name my-sscms -p 80:80 --restart=always -v C:\Users\zs851\source\repos\zstemplate\wwwroot:/app/wwwroot -e SSCMS_SECURITY_KEY=e2a3d303-ac9b-41ff-9154-930710af0845 -e SSCMS_DATABASE_TYPE=SQLite sscms/core:latest
```