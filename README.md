# ODOO-DOCKER

--docker-compose------

crear nuevo esqueleto-----------app
docker exec -it odoo_pos_web_1 /usr/bin/odoo scaffold chochos_app /mnt/extra-addons

dar permisos

sudo chmod -R 777 addons/
----------------------------

entrar al contenedor odoo modo admin

sudo docker exec –it odoo12 bash

entrar al contenedor db modo admin

sudo docker exec –it db12 bash

Ingresar al cliente por linea de comandos de PosgresSQL
psql –U odoo –d nombre_de_base_datos
---------------------------------------------------------------------------------------------------------------------------------
