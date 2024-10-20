### Crear contenedor de Postgres sin que exponga los puertos. Usar la imagen: postgres:11.21-alpine3.17
# COMPLETAR

![image](https://github.com/user-attachments/assets/3fd6a269-a2cb-467c-a916-76ee35cd98ff)

### Crear un cliente de postgres. Usar la imagen: dpage/pgadmin4

# COMPLETAR
![image](https://github.com/user-attachments/assets/f9af6d69-4b55-42b1-8b1b-1e215b781feb)


La figura presenta el esquema creado en donde los puertos son:
a: Puerto del contenedor pgadmin_client en la máquina host, que es 80 (puerto mapeado para pgAdmin).
b: Puerto interno de PostgreSQL que es el 5432 (puerto por defecto de PostgreSQL, aunque no se expone a la máquina host).
c: Puerto interno del contenedor pgAdmin4, que es 80 (para acceder a la interfaz de pgAdmin4).

![Imagen](img/esquema-ejercicio3.PNG)

## Desde el cliente
### Acceder desde el cliente al servidor postgres creado.
# COMPLETAR CON UNA CAPTURA DEL LOGIN
![image](https://github.com/user-attachments/assets/66ec5273-cc49-4ae4-ab3b-2fc6bd8e49a9)

![image](https://github.com/user-attachments/assets/631a1cea-d30d-46c6-9d3a-9093d8ac6bc1)

![image](https://github.com/user-attachments/assets/aaaa602f-f96a-4fa9-994a-6dc83d251ac6)

### Crear la base de datos info, y dentro de esa base la tabla personas, con id (serial) y nombre (varchar), agregar un par de registros en la tabla, obligatorio incluir su nombre.

![image](https://github.com/user-attachments/assets/4eb457f3-460a-4a20-9340-0f84bb9a732b)

## Desde el servidor postgresl
### Acceder al servidor
### Conectarse a la base de datos info
# COMPLETAR
### Realizar un select *from personas
# AGREGAR UNA CAPTURA DE PANTALLA DEL RESULTADO
![image](https://github.com/user-attachments/assets/73532452-0faa-4fa6-a892-5c256c914c70)
