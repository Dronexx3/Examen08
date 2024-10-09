# Usa la imagen oficial de PostgreSQL como base
FROM postgres:15-alpine

# Configura variables de entorno para PostgreSQL (opcional)
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=postgres
ENV POSTGRES_DB=votingapp

# Copia los scripts de inicialización en el directorio de entrada de PostgreSQL
# Estos scripts se ejecutan automáticamente cuando se inicializa la base de datos
# COPY ./init.sql /docker-entrypoint-initdb.d/

# Exponer el puerto de PostgreSQL
EXPOSE 5432

# Opcional: un punto de entrada personalizado o alguna configuración extra
CMD ["postgres"]