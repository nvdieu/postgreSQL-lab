# postgreSQL-lab
<h3 align="center">Cách tạo và chạy PostgreSQL bằng Docker</h3>
<h3 align="center">Trên cả Mac và Windows:</h3>


### b0: Cài đặt Docker Desktop
Tải Docker Desktop tại đây: [https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)

### b1: Cài đặt Pgadmin4
Tải Pgadmin4 tại đây: [https://www.pgadmin.org/download/)](https://www.pgadmin.org/download/))

### b2: Khởi động Docker trước khi tiếp tục 

### b3: Mở terminal (hoặc PowerShell trên Windows)
git clone : https://github.com/nvdieu/postgresql-lab.git

    cd postgreSQL-lab

    docker compose up -d

### b4: Khởi động PgAdmin 4

Thêm kết nối PostgreSQL trong pgAdmin
    Tab Connection:
        Host: postgres
        Port: 5432
        Username: admin
        Password: 1234

### b5 Dừng hệ thống
Khi không dùng nữa

Đóng Pgadmin4

Đóng container tại terminal (hoặc PowerShell trên Windows)

    docker compose down
