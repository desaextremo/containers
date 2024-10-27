FROM nginx

# Copia los archivos al directorio por defecto de Nginx
COPY index.html /usr/share/nginx/html/
COPY styles.css /usr/share/nginx/html/
COPY img /usr/share/nginx/html/img/

# Expone el puerto 80
EXPOSE 80

# Comando para ejecutar Nginx
# CMD: Esta instrucción define el comando por defecto que se ejecutará cuando el contenedor se inicie. En este caso, está iniciando Nginx.
# nginx: Este es el comando para ejecutar el servidor Nginx.
# -g "daemon off;": La opción -g permite pasar directivas directamente a Nginx al iniciar. La directiva daemon off; le indica a Nginx que se ejecute en primer plano, lo cual es necesario en los contenedores de Docker.
CMD ["nginx", "-g", "daemon off;"]
