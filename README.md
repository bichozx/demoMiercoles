# demoMiercoles

Repositorio de práctica para la creación del proyecto final de Backend 2, https://github.com/bichozx/demoMiercoles.

📌 Descripción

Este proyecto está desarrollado con Spring Boot y se conecta a una base de datos MySQL administrada con phpMyAdmin.
El objetivo es practicar la configuración de un backend con conexión a base de datos y el manejo de ramas en Git/GitHub para trabajo en equipo.

⚙️ Configuración de la base de datos

Nombre de la base de datos: practicamiercoles

Puerto: 3306

Gestor: phpMyAdmin/MySQL

Ejemplo de configuración en application.properties:
spring.application.name=demo
spring.datasource.url=jdbc:mysql://localhost:3306/practicamiercoles
spring.datasource.username=root
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update
