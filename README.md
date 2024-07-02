# Microservices na prática com Java Spring
## Projeto desenvolvido a partir da aula da Michelli Brito, Microservices na prática com Java Spring.

Esse projeto tem como objetivo desenvolver uma simples arquitetura de microsserviços:

* 🚀 Spring Boot 3.3.1
* ☕ Java version 17
* ☁️ CloudAMQP
* ✉️ RabbitMQ
* 🌿 Spring Mail

A arquitetura foi desenvolvida com dois microsserviços, ms-user e ms-email. Com o endpoint POST /users, deve ser possível cadastrar um novo usuário, e após esse cadastro 
deve ser enviado uma mensagem que ao passar pelo RabbitMQ será encaminhada para o ms-email, que em seguida disparará um e-mail de boas vindas para o e-mail do novo
usuário cadastrado.

A aula da Michelli Brito pode ser vista no link a seguir: https://youtu.be/ZnECi2gatMs?si=BHStoPlBbVepHo5j
