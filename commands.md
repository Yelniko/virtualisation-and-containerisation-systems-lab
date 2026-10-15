
commands.md
lab3
README.md
8d3415872b60d83904f5ade1e1a0b003111a82c31769fc66750bf01296223e6f
CONTAINER ID   IMAGE            COMMAND                  CREATED          STATUS                       PORTS                                     NAMES
8d3415872b60   lab3-nginx:1.0   "nginx -g 'daemon of…"   11 seconds ago   Up 10 seconds                0.0.0.0:8080->80/tcp, [::]:8080->80/tcp   lab3-web
efe07405ac32   postgres:18.6    "docker-entrypoint.s…"   4 weeks ago      Up About an hour (healthy)   127.0.0.1:5433->5432/tcp                  postgres
d48eafaba457   redis:8.10.1     "docker-entrypoint.s…"   4 weeks ago      Up About an hour (healthy)   127.0.0.1:6380->6379/tcp                  redis

HTTP/1.1 200 OK
Server: nginx
Date: Thu, 15 Oct 2026 12:02:05 GMT
Content-Type: text/html
Content-Length: 1813
Last-Modified: Thu, 15 Oct 2026 11:57:27 GMT
Connection: keep-alive
ETag: "6ad0bfa7-715"
Accept-Ranges: bytes

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Server Status</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 min-h-screen flex items-center justify-center p-4">

    <div class="bg-slate-900/80 border border-slate-800 rounded-2xl p-6 sm:p-8 md:p-12 shadow-2xl max-w-md w-full text-center backdrop-blur-sm">

        <h1 class="text-2xl sm:text-3xl font-bold tracking-tight text-white mb-4">
            Лабораторна робота №3
        </h1>

        <p class="text-slate-400 text-xs sm:text-sm leading-relaxed mb-2">
            Студента: Ельнікова Олега
        </p>

        <p class="text-slate-400 text-xs sm:text-sm leading-relaxed mb-3">
            Група: 6.1214-пі2
        </p>
        
        <p class="text-slate-400 text-xs sm:text-sm leading-relaxed mb-3">
            Курс: 3
        </p>
        
        <p class="text-slate-400 text-xs sm:text-sm leading-relaxed mb-3">
            Вариант: 5
        </p>
        
        <p class="text-slate-300 text-xs sm:text-sm font-medium text-center mb-6">
            Version: 1.0
        </p>

        <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-emerald-500/10 border border-emerald-500/20 text-emerald-400 text-xs font-semibold">
            <span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
            Status: 200 OK
        </div>
    </div>
</body>
</html>
Login Succeeded
IMAGE          CREATED          CREATED BY                                      SIZE      COMMENT
d9dc9750371c   6 minutes ago    CMD ["nginx" "-g" "daemon off;"]                0B        buildkit.dockerfile.v0
<missing>      6 minutes ago    EXPOSE [80/tcp]                                 0B        buildkit.dockerfile.v0
<missing>      6 minutes ago    COPY ./index.html /var/www/html/index.html #…   20.5kB    buildkit.dockerfile.v0
<missing>      42 minutes ago   RUN /bin/sh -c apt-get update  && apt-get in…   10.9MB    buildkit.dockerfile.v0
<missing>      42 minutes ago   WORKDIR /opt/lab3                               12.3kB    buildkit.dockerfile.v0
<missing>      42 minutes ago   USER root                                       0B        buildkit.dockerfile.v0
<missing>      42 minutes ago   LABEL version=1.0 preformer= group=             0B        buildkit.dockerfile.v0
<missing>      10 days ago      # debian.sh --arch 'amd64' out/ 'trixie' '@1…   87.7MB    debuerreotype 0.17
Login Succeeded
The push refers to repository [docker.io/foresterclaus/debian-nginx]
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
44136fa355b3: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
ecc510c1e359: Waiting
682a76754c44: Waiting
f0e746b2b003: Waiting
f0e746b2b003: Waiting
ecc510c1e359: Waiting
44136fa355b3: Pushed
3b9c1b1e6c9e: Waiting
3b9c1b1e6c9e: Waiting
0d0ced80087d: Waiting
682a76754c44: Pushed
3b9c1b1e6c9e: Waiting
3b9c1b1e6c9e: Waiting
f0e746b2b003: Pushed
0d0ced80087d: Waiting
0d0ced80087d: Waiting
3b9c1b1e6c9e: Waiting
3b9c1b1e6c9e: Waiting
0d0ced80087d: Waiting
0d0ced80087d: Waiting
3b9c1b1e6c9e: Waiting
0d0ced80087d: Waiting
0d0ced80087d: Waiting
0d0ced80087d: Waiting
0d0ced80087d: Pushed
