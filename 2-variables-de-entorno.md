# Variables de Entorno
### ¿Qué son las variables de entorno
# COMPLETAR

### Para crear un contenedor con variables de entorno?

```
docker run -d --name <nombre contenedor> -e <nombre variable1>=<valor1> -e <nombre variable2>=<valor2>
```

### Crear un contenedor a partir de la imagen de nginx:alpine con las siguientes variables de entorno: username y role. Para la variable de entorno rol asignar el valor admin.

# COMPLETAR

# CAPTURA CON LA COMPROBACIÓN DE LA CREACIÓN DE LAS VARIABLES DE ENTORNO DEL CONTENEDOR ANTERIOR

![image](https://github.com/user-attachments/assets/ad90e11e-6550-4ec3-ad18-93e412199b18)


### Crear un contenedor con mysql:8 , mapear todos los puertos

![image](https://github.com/user-attachments/assets/fc3afd3a-d6b4-411b-bc4e-261be91a4ed7)



### ¿El contenedor se está ejecutando?
# COMPLETAR
![image](https://github.com/user-attachments/assets/d271acc5-b18e-4865-a2eb-c0661e7816aa)


### Identificar el problema
# COMPLETAR
![image](https://github.com/user-attachments/assets/cc824f5c-80e4-41ad-8fbb-1f96475902ef)

### Eliminar el contenedor creado con mysql:8 
# COMPLETAR
![image](https://github.com/user-attachments/assets/2cd0b847-bd01-4941-9b08-e7071e767cea)

### Para crear un contenedor con variables de entorno especificadas
- Portabilidad: Las aplicaciones se vuelven más portátiles y pueden ser desplegadas en diferentes entornos (desarrollo, pruebas, producción) simplemente cambiando el archivo de variables de entorno.
- Centralización: Todas las configuraciones importantes se centralizan en un solo lugar, lo que facilita la gestión y auditoría de las configuraciones.
- Consistencia: Asegura que todos los miembros del equipo de desarrollo o los entornos de despliegue utilicen las mismas configuraciones.
- Evitar Exposición en el Código: Mantener variables sensibles como contraseñas, claves API, y tokens fuera del código fuente reduce el riesgo de exposición accidental a través del control de versiones.
- Control de Acceso: Los archivos de variables de entorno pueden ser gestionados con permisos específicos, limitando quién puede ver o modificar la configuración sensible.

Previo a esto es necesario crear el archivo y colocar las variables en un archivo, **.env** se ha convertido en una convención estándar, pero también es posible usar cualquier extensión como **.txt**.
```
docker run -d --name <nombre contenedor> --env-file=<nombreArchivo>.<extensión> <nombre imagen>
```
**Considerar**
Es necesario especificar la ruta absoluta del archivo si este se encuentra en una ubicación diferente a la que estás ejecutando el comando docker run.

### Crear un contenedor con mysql:8 , mapear todos los puertos y configurar las variables de entorno mediante un archivo
# COMPLETAR

![image](https://github.com/user-attachments/assets/7caacc65-f518-427b-90e9-3a8bf3065cfe)

# CAPTURA CON LA COMPROBACIÓN DE LA CREACIÓN DE LAS VARIABLES DE ENTORNO DEL CONTENEDOR ANTERIOR 

![image](https://github.com/user-attachments/assets/7b30c419-b195-4633-b5a8-b9b868c71a54)

### ¿Qué bases de datos existen en el contenedor creado?
# COMPLETAR
![image](https://github.com/user-attachments/assets/4ec017db-231c-430c-9ade-98c21d2da0ac)
