# Taller 1 AYGO

Mini APP para dockerizar un aplicativo Java con springboot para obtener un Hello World via HTTP

## Tecnologias

- Apache Maven: 3.9.1
- Java: 17
- Spring-boot: 3.2.5
- Docker

## Correr el proyecto

Descargar o clonar el proyecto y entrar a la carpeta Root.

### Inicializar el Backend

#### Mediante Maven y Java
Dentro de la carpeta root del proyecto correr el siguiente comando

`mvn clean install`

Despues de que termine de compilar, ejecutar el siguiente comando en la misma carpeta root

`java -cp "target/classes;target/dependency/*" co.edu.escuelaing.springdockerdemolive.RestServiceApplication`

#### Mediante Docker

`docker run -d -p 42000:33025 --name firstdockerimageaws derja/firstspringwebapprepo`

## Pruebas de despliegue

### Grupo de seguridad
![{C2E28ED9-F479-4968-9D9B-99C35E615538}](https://github.com/user-attachments/assets/efc10948-a89d-4b70-b7b3-4012ec59525f)

### Instancia de VM
![{82CD8BE7-4773-4D1D-82F9-8CF44A11ADC1}](https://github.com/user-attachments/assets/d7b4c861-31c5-474f-9ff2-bc42e856bfb0)

### Docker corriendo en VM
![{7938D893-747B-4506-A086-21F0C138BFF6}](https://github.com/user-attachments/assets/9824e0d4-5aef-476e-91f0-6dc5b3eadcf1)

### Accediendo a la URL mediante un browser
![{5C9EB68D-ECEE-4114-8118-EF3FE9B476F8}](https://github.com/user-attachments/assets/a774d07b-8ee8-41d6-aa05-12017a87ef44)
![{B42706DF-DFCA-4C10-98C3-4D357A50A255}](https://github.com/user-attachments/assets/c773dd7d-6c67-494d-a88d-4d2ae9225a57)

# Author

Daniel Esteban Ramos Jimenez

# Version
1.0
