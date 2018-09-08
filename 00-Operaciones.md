# OpenSaturday
## Laboratorio MongoDB
### Es importante que el participante tenga una maquina virtualizada con Linux 
### (No importa la distro)


**1. Entrar al Shell de MongoDB**

```mongo``` O ```./mongo```

**2. Mostrar lista de las base datos**

```show dbs```

**3. Crear una base de datos**

```use nombre-base-de-datos```

**4. Saber la base de datos actual que estamos conectado**

```db```

**5. Eliminar una base de datos**

Si queremos eliminar la base de datos llamada ejemplos, primero la seleccionamos y luego se elimina

```use ejemplo```
```db.dropDatabase()```

**6. Para saber las colecciones que existen dentro una base de datos**

```show collections```

**7.Para insertar datos en una coleccion**

Primero elegimos la base de datos donde vamos a trabajar:

```use datosejemplo```

Ahora procedemos a insertar registros

```db.datos.insert({"estatus": "presente"})```

**8.Para eliminar una coleccion**

Desde la base de datos ejecutamos

```db.nombrecoleccion.drop()```

**9. Para realizar el equivalente a un show * en una coleccion**

```db.coleccion.find()```

**10. Para realizar una find por un campo especifico**

```db.coleccion.find({"campo" : "valor"})```

**11. Para importar un archivo json a una coleccion**

```mongoimport -d base-de-datos -c coleccion archivo,json```

**12. Para hacer backup**

```mongodump -d base-de-datos -o /ruta```

**13.Actualizar en MongoDB**

```>db.coleccion.save({_id:ObjectId(),nuevos-datos})```

**14.Remover en MongoDB**


```db.coleccion.remove(criterio-borrar,1)``

