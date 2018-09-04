# osmongolab
## Es importante que el participante tenga una maquina virtualizada con Linux (No importa la distro)


1. Crear directorio /opensaturday 

sudo mkdir opensaturday

Nota: Solo para este lab otorgar permiso 777 al directorio /opensaturday

sudo chmod 777 -R /opensaturday


2. Entramos al directorio opensaturday

cd opensaturday


3. Descargamos MongoDB

wget https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-4.0.1.tgz


4. Descomprimir el archivo tgz

tar zxvf mongodb-linux-x86_64-4.0.1.tgz



5. Si ejecuta ls -lA se puede ver un directorio con este nombre:

mongodb-linux-x86_64-4.0.1

Ahora procedemos a renombrar dicho directorio

mv mongodb-linux-x86_64-4.0.1 mongodb-linux


6. Creamos los directorios principales

sudo mkdir -p etc data logs run


7. Ahora creamos algunos sub-directorios

sudo mkdir -p data/db01 data/db02 data/db03

sudo mkdir -p logs/log01 logs/log02 logs/03

sudo mkdir -p run/run01 run/run02 run/run03


8. En este repositorio existen 3 archivos llamados mongod01.conf, mongodb02.conf y mongodb03.conf. Debe descargar dichos archivos y colocarlos
dentro del directorio /opensaturday/etc



