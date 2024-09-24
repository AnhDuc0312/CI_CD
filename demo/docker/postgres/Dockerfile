# Sử dụng image PostgreSQL chính thức
FROM postgres:15

# Copy file init.sql để khởi tạo database và user
COPY ./docker/postgres/init.sql /docker-entrypoint-initdb.d/
