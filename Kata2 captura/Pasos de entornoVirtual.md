# Como crear un entorno Virtual

  

## Hay que tener en cuenta los siguientes pasos

  

1.  Tener o Crear un folder para alojar nuestro proyecto de entorno virtual

2. Insertar el siguiente comando python3 -m venv env de la linea de comando del proyecto

	**Nota:** venv es la paquetería o modulo del entorno virtual.
	
	**Consejo:** "env" es una ejemplificación de como puedes llamar a tu entorno virtual, en mi caso se llama "launchx".
	
3. Después de la instalación de la paquetería de virtualenv, se procede a activar el entorno virtual con el siguiente comando:
	`	c:\Users\xxxxx\Desktop\nombre_de_nuestro_folder\> launchx\Scripts\activate` 
		
	**Ojo:** Hay que tomar en cuenta que "launchx" fue el nombre que le asignamos a nuestro entorno virtual.

4. **¿Como saber que nuestro entorno virtual esta activo?**, pues lo podremos notar cuando aparezca una leyenda del entorno virtual entre parentesis () 
	`(launchx) PS c:\Users\xxxxx\Desktop\nombre_de_nuestro_folder\`
	 
5. Procedemos a instalarle un paquete llamado `python-dateutil` con el siguiente comando:
	`pip install python-dateutil`
	**Nota:** Este comando descargará e instalará `dateutil`, un paquete para analizar el formato de archivo .yml.
 6. Para ver qué paquetes están ahora instalados en tu entorno virtual, puedes ejecutar `pip freeze`. Este comando produce una lista de paquetes instalados en el terminal:

```
# Mensaje de salida en consola
  python-dateutil==2.8.2
  six==1.16.0
```
7. Para salir de ese entorno virtual, ingresaremos el comando `deactivate`
	`	c:\Users\xxxxx\Desktop\nombre_de_nuestro_folder\> launchx\Scripts\deactivate` 

## Anexo evidencia de la Kata realizada
```
![Texto alternativo](Kata2 img/Entorno Virtual Python.jpeg )