# comandos-que-uso-

docker exec -it NOMBRE_CONTENEDOR mysql -u root -p

python -m pwiz -e mysql -u root -P -H localhost pyme > datos/modelos/models.py

docker run -d --name mysql-pyme
-e MYSQL_ROOT_PASSWORD=tu_clave
-e MYSQL_DATABASE=pyme
-p 3306:3306
-v mysql_data:/var/lib/mysql
mysql:8

en la terminal poner estos comandos

py -m venv .venv

.venv\Scripts\Activate.ps1

python -m pip install -r requirements.txt

python -m venv .venv

 source .venv/bin/activate

 omarchy-theme-bg-set ~/Downloads/fondolinux.jpg
