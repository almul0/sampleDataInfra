FROM postgres:11-alpine

COPY restaurants.sql /restaurants.sql
ENV PGPASSWORD=postgres
CMD psql -h postgreSQL -d postgres -U postgres -f restaurants.sql
