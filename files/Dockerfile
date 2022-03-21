From mysql:8.0.28
LABEL version="1.0" description="MySQL Service" by="DBA RAY"
RUN touch /var/log/mysqld.log
RUN touch /var/log/slow.log
RUN chown -R mysql:mysql /var/log/mysqld.log
RUN chown -R mysql:mysql /var/log/slow.log