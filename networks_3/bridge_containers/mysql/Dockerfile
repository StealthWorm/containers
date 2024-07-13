FROM mysql:5.7

#/docker-entrypoint-initdb.d/ é um diretorio do container para rodar scripts de banco
COPY schema.sql /docker-entrypoint-initdb.d/

EXPOSE 3306

VOLUME ["/backup/"]