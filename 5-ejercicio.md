## Esquema para el ejercicio
![Imagen](img/esquema-ejercicio5.PNG)

### Crear la red

![image](https://github.com/user-attachments/assets/aa2cbc52-5f29-4fcc-a935-dcf6d64fe2cf)

### Crear el contenedor mysql a partir de la imagen mysql:8, configurar las variables de entorno necesarias

![image](https://github.com/user-attachments/assets/1ea8269f-4fee-49d9-823e-2d7e450c77ec)

### Crear el contenedor wordpress a partir de la imagen: wordpress, configurar las variables de entorno necesarias

![image](https://github.com/user-attachments/assets/e3c44c1e-4220-4a70-ae13-b885d811ec79)

De acuerdo con el trabajo realizado, en la el esquema de ejercicio el puerto a es 9300

Ingresar desde el navegador al wordpress y finalizar la configuración de instalación.

![image](https://github.com/user-attachments/assets/4aaa62dc-5a96-4609-9be5-65f0a58df097)

Desde el panel de admin: cambiar el tema y crear una nueva publicación.
Ingresar a: http://localhost:9300/ 
recordar que a es el puerto que usó para el mapeo con wordpress

![image](https://github.com/user-attachments/assets/f2dffe58-e719-4632-bce7-61984070ac55)

### Eliminar el contenedor wordpress

![image](https://github.com/user-attachments/assets/b004ea82-53fe-4f13-941e-f493efdac725)

### Crear nuevamente el contenedor wordpress

![image](https://github.com/user-attachments/assets/d860abbd-f068-4cfa-8b14-b61a443b5a0a)

Ingresar a: http://localhost:9300/ 
recordar que a es el puerto que usó para el mapeo con wordpress

### ¿Qué ha sucedido, qué puede observar?
Al acceder nuevamente la configuración anterior ya no está disponible. Esto ocurre porque al eliminar el contenedor los datos del contenedor de WordPress se pierden ya que no se ha configurado ningún volumen para persistir los datos de WordPress.




