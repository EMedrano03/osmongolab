# OpenSaturday
## Laboratorio MongoDB
### Es importante que el participante tenga una maquina virtualizada con Linux 
### (No importa la distro)


**1. Crear directorio /opensaturday**

```sudo mkdir /opensaturday```

Nota: Solo para este lab otorgar permiso 777 al directorio /opensaturday

```sudo chmod 777 -R /opensaturday```


**2. Entramos al directorio opensaturday**

```cd opensaturday```


**3. Descargamos MongoDB**

```wget https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-4.0.1.tgz```


**4. Descomprimir el archivo tgz**

```tar zxvf mongodb-linux-x86_64-4.0.1.tgz```


**5. Si ejecuta ls -lA se puede ver un directorio con este nombre:**

mongodb-linux-x86_64-4.0.1

Ahora procedemos a renombrar dicho directorio

```mv mongodb-linux-x86_64-4.0.1 mongodb-linux```


**6. Creamos los directorios principales**

```mkdir -p etc data logs run```


**7. Ahora creamos algunos sub-directorios**

```mkdir -p data/db01 data/db02 data/db03```

```mkdir -p logs/log01 logs/log02 logs/03```

```mkdir -p run/run01 run/run02 run/run03```


**8. En este repositorio existen 3 archivos dentro de etc llamados mongod01.conf, mongodb02.conf y mongodb03.conf. Debes descargar dichos archivos y colocarlos dentro del directorio /opensaturday/etc**

## MongoDB Compasss

Usaremos la version 1.15.1 (Stable) sobre ubuntu 16.04 Desktop

Se puede descargar desde https://www.mongodb.com/download-center?jmp=hero#compass

*Si usas Windows, igual puedes elegir el instalador para Windows*



