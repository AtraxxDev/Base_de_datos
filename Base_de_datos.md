# <center> Base de datos Jugadores de League Of Legends </center>

## Entidades
<h2>  Jugadores</h2>

- Jugadores_id (PK)
- Nombre
- Fecha de Nacimiento
- Pais (FK)
- Server (FK)
- Posicion (FK)
- Campeon (FK)
- Liga (FK)


<h2>  Liga <FK> </h2>

- Liga_ID (PK)
- Region
- Liga (FK)


<h2>  Pais </h2>

- Pais_ID (PK)

- Nombre

- Dominio

<h2>  Campeones </h2>

- Campeones_ID (PK)
- Nombre del camepeon 
- Region del campeon
- Tipo de campeon 

<h2>  SERVERS </h2>

- SERVERS_ID (PK)
- Nombre del Servidor

<h2>  Posicion </h2>

- Posicion_ID (PK)
- Carril

<h2>  RELACIONES </h2>

- SERVERS_ID (PK)
- Nombre del Servidor
