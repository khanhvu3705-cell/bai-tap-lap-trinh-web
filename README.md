# BAI TAP LAP TRINH WEB

## 1. Gioi thieu
Du an thuc hanh lap trinh web su dung Docker va cac dich vu:
- Nginx: Web server.
- Node-RED: Xu ly API.
- MariaDB: Quan ly co so du lieu.
- phpMyAdmin: Quan ly MariaDB.

## 2. Cau truc thu muc
- cloudflared/
- nginx/conf.d/
- nodered/
- website1/
- website2/
- docker-compose.yml
- README.md

## 3. Cac dich vu

| Dich vu | Dia chi |
|---|---|
| Website 1 | http://localhost:8080 |
| Website 2 | http://website2.local:8080 |
| Node-RED | http://localhost:1880 |
| phpMyAdmin | http://localhost:8081 |

## 4. Cai dat va chay

Chay lenh:

    sudo docker compose up -d

Kiem tra container:

    sudo docker ps

## 5. Luu y
- Khong cong khai file .env.
- Khong cong khai mat khau hoac Cloudflare token.
- Du lieu MariaDB duoc luu trong Docker volume mariadb_data.
