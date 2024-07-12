# Web-Server
Tutorial How to Install Web-server
# Install Web server



```bash
Sudo apt update
sudo apt-get install nginx
```

```sh
-> Open by External IP 

How to Configure nginx
-> sudo nano /var/www/html/index.nginx-debian.html
-> Costum by your own

<!DOCTYPE html>
<html>
<head>
<title>Welcome to nginx!</title>
<style>
    body {
        width: 35em;
        margin: 0 auto;
        font-family: Tahoma, Verdana, Arial, sans-serif;
    }
</style>
</head>
<body>
<h1>Welcome to nginx!</h1>
<h2>Let's build great app with Google Cloud!</h2>
<p>If you see this page, the nginx web server is successfully installed and
working. Further configuration is required.</p>
 
<p>For online documentation and support please refer to
<a href="http://nginx.org/">nginx.org</a>.<br/>
Commercial support is available at
<a href="http://nginx.com/">nginx.com</a>.</p>
 
<p><em>Thank you for using nginx.</em></p>
</body>
</html>


->how to clean up?
-> Delete your select Instance


