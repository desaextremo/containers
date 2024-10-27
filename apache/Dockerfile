# Usa la imagen oficial de Apache (httpd)
FROM httpd:latest

# Copia los archivos HTML, CSS y la carpeta img al directorio por defecto de Apache
COPY index.html /usr/local/apache2/htdocs/
COPY styles.css /usr/local/apache2/htdocs/
COPY img /usr/local/apache2/htdocs/img/

# Expone el puerto 80
EXPOSE 80

# Apache ya se ejecuta en primer plano por defecto, no es necesario el CMD adicional.

