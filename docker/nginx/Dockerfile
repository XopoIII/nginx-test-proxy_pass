FROM nginx:1.23.1
# это гавно не устанавливается если на сервере заблокирвоан 80 порт! внимательно!
RUN apt-get update && apt-get install -y nginx-extras libnginx-mod-http-image-filter libnginx-mod-http-ndk
CMD ["nginx", "-g", "daemon off;"]
