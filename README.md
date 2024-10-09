# ActividadRepaso
#docs
springdoc.api-docs.path=/v3/api-docs
springdoc.swagger-ui.path=/swagger-ui.html
server.address=0.0.0.0
#server
server.port= 9090

# spring.jpa.hibernate.ddl-auto: specifies the strategy for creating and dropping database tables
spring.jpa.hibernate.ddl-auto = create-drop
spring.jpa.show-sql=true

spring.datasource.url = jdbc:mysql://127.0.0.1:3306/estudiante

# spring.datasource.username: specifies the username for the Mysql database connection
spring.datasource.username = root

# spring.datasource.password: specifies the password for the Mysql database connection
spring.datasource.password = admin1234

spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
