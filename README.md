# so-exam3

**Nombre:** Angie Lorena Pérez    
**Código:** A00242068  
**Materia:** Sistemas operacionales  
**Correo:** lorena9221@hotmail.com  
**Repositorio:** https://github.com/AlorenaP/so-exam3


#3 Implementación de un servicio web en Flask que cumpla las siguientes condiciones:
Se crea un ambiente virtual para el desarrollo el cual contiene las dependencias necesarias, con el comando 
```$ python3 -m venv flaskamb ```
flaskamb es el nombre del ambiente virtual que se va a usar el cual se activa co el comando
``$ source flaskamb/bin/activate``
luego se agregan los archivos requirements.txt y requirements_dev.txt utilizando el codigo fuente que esta almacenado en el repositorio de microservices. Luego la carpeta **op_stats** va contener los archivos de python llamados app.py(en este archivo se se crean los métodos que permiten realizar la implementación del servicio web de flaksk) y el stats.py (en este archivo se encuntran los metodos que retornan los estados de la memoria, disco duro y la CPU)

En la clase app.py y en stats.py

![](Imagenes/metodos.png) 

Ahora en postman se evidencia el funcionamiento del API haciendo las peticiones

  - Para CPU
  ![](Imagenes/postmancpu.png)
  
  - Para RAM
  ![](Imagenes/postmanRam.png)
  
  - Para Disco
  ![](Imagenes/postmanDisk.png)
  
  
 #4 Para las pruebas unitareas se crea el archivo llamado test_stats.py que contiene las pruebas unitarias del servicio. Estas
 se corren usando el comando de pytest, el cual busca las pruebas disponibles dentro del directorio:
 ``$ pytest -v``
 
 **obteniendo**
 
 ![](Imagenes/pytest.png)
 
 #5 

