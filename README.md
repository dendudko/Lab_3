# Config
```
server {
listen 80;

root /var/www/html/sit/app1;
}

server {
listen 7777 default_server;

root /var/www/html/sit/app1;

location /docs {
alias /var/www/html/sit/app2;
}
}
```
# Ссылки
`http://62.113.106.241`<br>
`http://62.113.106.241:7777/docs/`
