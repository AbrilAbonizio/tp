# Propuesta TP DSW

## Grupo
### Integrantes
* 51153 - Abonizio, Abril
* 51898 - Mestre, Marcos

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
* GoTogether es una plataforma web colaborativa donde los usuarios pueden organizar o unirse a viajes grupales para compartir gastos (transporte y alojamiento). El objetivo es reducir costos de viaje conectando personas con intereses similares y destinos comunes.

### Modelo
![image](https://github.com/user-attachments/assets/e1875827-1b36-4af0-866d-a45d98d0c10c)
(https://github.com/user-attachments/assets/6283a64f-09f8-457f-a1eb-453ae81db704)


https://drive.google.com/file/d/1evRcORRES3nPpAhUdvk0pCf8hHf_FCY7/view?usp=drive_link

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Pasajero<br>2. CRUD Categoría<br>3. CRUD Ciudad|
|CRUD dependiente|1. CRUD Viaje {depende de} CRUD Pasajero, Categoría y Ciudad
|Listado<br>+<br>detalle| 1. Listado de Viajes disponibles filtrados por Categoría, muestra nombre de Ciudad, descripción de Viaje, fecha de salida y llegada, cupo disponible y costo del viaje<br>
|CUU/Epic|1. Registrar solicitud de viaje <br> 2. Aceptar o Rechazar solicitud (Reemplaza CRUD Dependiente) VER

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Pasajero<br>2. CRUD Viaje<br>3. CRUD Categoria<br>4. CRUD Ciudad<br>5. CRUD Solicitud<br>6. CRUD Gasto<br>|
|CUU/Epic|1. Registrar solicitud de viaje<br>2. Cargar gastos de viaje <br> VER3. |


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Mostrar viajes disponibles que tengan como organizador un pasajero con determinada calificación o mayor <br>2. Listar ciudades más solicitadas por los usuarios|
|CUU/Epic|1. Cancelar Viaje<br>2. VER |
|Otros|1. Seguimiento del viaje|

