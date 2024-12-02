<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRZLCc_7YH-7urnc8N7_5YCR9JhWEiA6qTrCM55UPPXjg&s" alt="Club Deportivo Ciudad de los Angeles - ¡Somos ciudad!" width="250px">
</div>

# System Management - Somos Ciudad

This project aims to develop the frontend for the CA Sports Center website, built with Vite, React, and Tailwind. Below are the technical requirements and main functionalities requested by our client.

## Technologies Used

### Prototyping in Figma

<a href="#" rel="nofollow"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/figma-colored.svg" width="36" height="36" alt="Figma" style="max-width: 100%;"></a>

### Programming Languages

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)  ![JAVASCRIPT](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

### Frameworks and Libraries

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Databases

<a href="#"><img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=101010" alt="MongoDB"></a>

### Testing Tools

<a href="#"><img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white&labelColor=101010" alt="Postman"></a>
<a href="#"><img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white&labelColor=101010" alt="Jest"></a>
<a href="#"><img src="https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white&labelColor=101010" alt="Cypress"></a>

## Technical Requirements ⚙️

### Framework

- Work under the Scrum framework.

### User Authentication

- Implement secure user authentication using JWT or another suitable method.

### Student Representative Functions

- **Children Registration**: Allow registering children with details such as age, height, weight, sex, clothing size, etc.
- **Admission Requests**: Submit requests to be accepted or rejected by the administrator due to limited spots.
- **Required Materials List**: View and request missing materials or clothing for the student.
  - Photos of available clothing.
  - List of clothes by size.
  - Bank account info for payments.
  - Attach PDF payment receipt.
  - Import purchased clothing list.
- **Document Signing**: Manage LOPD and image rights documents.
- **View Payment Sections**: Review completed payments.

### Additional Features for Members

- **Annual Payments**: Display the status (positive or negative) of the three annual payments.

### Administrator Functions

- **Manage Admission Requests**: Accept or reject admission requests.
- **Member List**: View member information (name, surname, ID, enrollment method).
- **Download Forms**: Download forms for those wishing to become members.

### Informational Web Pages

- General club information.
- First and second team details.
- Youth football information.
- Form to become a member.
- Club history.
- Club store.
- Contact.

### Installation and Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/angarce25/centro-deportivo-front.git
   ```

2. **Clone the Backend Repository**

   ```bash
   git clone https://github.com/carlaprimola/centro-deportivo-back.git
   ```

3. **Install Dependencies**

   ```bash
   npm install
   ```

4. **Start the Client**

   ```bash
   npm run dev
   ```

5. **Configure the Database** according to the provided instructions.

<h4 id="version-control">Version Control</h4>
<p><a href="#"><img src="https://img.shields.io/badge/git%20-%23F05033.svg?&amp;style=for-the-badge&amp;logo=git&amp;logoColor=white&amp;labelColor=101010" alt="Git"></a>
<a href="#"><img src="https://img.shields.io/badge/github%20-%23121011.svg?&amp;style=for-the-badge&amp;logo=github&amp;logoColor=whit&amp;logoColor=white&amp;labelColor=101010" alt="Github"></a></p>

# git branches
   ![Badge en Desarollo](https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green)

| BRANCH   | Description                                                                           |
| -------- | ------------------------------------------------------------------------------------- |
| main     | Main branch. Contains final results.                                                 |
| develop  | Branch for developments in progress.                                                 |
| origin/feature/auth | Branch for token management and user registration, login |
| origin/feature/admin-dash | Branch for token integration with admin functionalities |
| origin/feature/footer | Footer UI branch |
| origin/feature/header | Header UI and contact functionalities branch |
| origin/feature/sidebar | Admin and user sidebar UI branch |
| origin/feature/design | General design for component styles branch |
| origin/feature/form-player  | Player form styling and functionality |
| origin/feature/forms | User registration and login form styling and functionality |
| origin/feature/home | Homepage UI branch |
| origin/feature/merchandising | Merchandising UI without login |
| origin/feature/new-player-form-integration | Player form integration branch |
| origin/feature/order-users  | User purchase UI branch |
| origin/feature/players | Admin functionalities to view players |
| origin/feature/products | Admin view for product orders |
| origin/feature/resources | UI resources for general components |
| origin/feature/sidebar | UI and functionality for sidebar |
| origin/feature/terms-and-conditions | UI for terms and conditions under LOPD |
| origin/feature/user-profile | User profile UI and functionalities |
| origin/feature/users-and-players-view | Linked user and player info UI |
| origin/feature/orders-detail-view | Detailed product order view |
| origin/feature/order-pdf | Attach PDF to product payment UI |
| origin/readme | README modifications branch |
| origin/test/e2e | Frontend end-to-end testing branch |
| origin/chore/security-sanitization | Extra security UI functionalities |
| origin/security/decode| Token verification UI branch |

# Planning

- Task planning on Trello
- Daily Standups
- Sprints
- All for one.

# Our Team

- Carla Escobar (https://github.com/carlaprimola)
- Leandra Montoya (https://github.com/leamontoya19)
- Andrea García (https://github.com/angarce25)
- Fiorella Sandoval (https://github.com/FiorellaSF)
- Alvaro González (https://github.com/agt1984)
- Isaac García Adjuntar (https://github.com/Isarok)
- Abelardo Acosta (https://github.com/Moriarty369)

## Contributing

To contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push your changes to the repository (`git push origin feature/new-feature`).
5. Create a new Pull Request.
6. You will be notified about the request by the

 development team.

## License

This project is licensed. For more details, please check the LICENSE file.

---
<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRZLCc_7YH-7urnc8N7_5YCR9JhWEiA6qTrCM55UPPXjg&s" alt="Club Deportivo Ciudad de los Angeles - ¡Somos ciudad!" width="250px">
</div>

# Sistema de Gestión - Somos Ciudad

Este proyecto tiene como objetivo desarrollar el frontend para el sitio web del Centro Deportivo CA, implementado con Vite, React y Tailwind. A continuación, se detallan los requisitos técnicos y las funcionalidades principales solicitadas por nuestro cliente.

## Tecnologías Utilizadas

### Creación de prototipos en Figma.

<a href="#" rel="nofollow"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/figma-colored.svg" width="36" height="36" alt="Figma" style="max-width: 100%;"></a>

### Lenguajes de Programación

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)  ![JAVASCRIPT](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

### Frameworks y Librerías

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Bases de Datos

<a href="#"><img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=101010" alt="MongoDB"></a>

### Herramientas de Testing

<a href="#"><img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white&labelColor=101010" alt="Postman"></a>
<a href="#"><img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white&labelColor=101010" alt="Jest"></a>
<a href="#"><img src="https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white&labelColor=101010" alt="Cypress"></a>

## Requisitos Técnicos ⚙️

### Marco de Trabajo

- Trabajo bajo el marco Scrum.

### Autenticación de Usuarios

- Implementar autenticación segura de usuarios usando JWT u otro método adecuado.

### Funciones del Representante del Alumno

- **Registro de Hijos**: Permitir registrar a sus hijos con datos como edad, altura, peso, sexo, talla de ropa, etc.
- **Solicitud de Ingreso**: Hacer solicitudes de ingreso que serán aceptadas o rechazadas por el administrador debido a cupos limitados.
- **Listado de Material Obligatorio**: Ver y solicitar material o prendas faltantes para el alumno.
  - Fotos de las prendas disponibles.
  - Listado de ropa por tallas.
  - Información de la cuenta bancaria para pagos.
  - Adjuntar justificante de pago en PDF.
  - Importar listado de prendas compradas.
- **Firma de Documentos**: Gestionar documentos de LOPD y derechos de imagen.
- **Ver Apartados de Pagos Hechos**: Revisar pagos realizados.

### Funciones Extras para Socios

- **Pagos Anuales**: Mostrar estado (positivo o negativo) de los tres pagos anuales de los socios.

### Funciones del Administrador

- **Gestión de Solicitudes de Ingreso**: Aceptar o rechazar solicitudes de ingreso.
- **Listado de Socios del Club**: Ver información de socios (nombre, apellidos, DNI, forma de alta).
- **Descarga de Formularios**: Descargar formularios de quienes desean convertirse en socios.

### Páginas Web Informativas

- Información general del club.
- Información del primer y segundo equipo.
- Información de fútbol base.
- Formulario para convertirse en socio.
- Historia del club.
- Tienda del club.
- Contacto.

### Instalación y Configuración

1. **Clonar el Repositorio**

   ```bash
   git clone https://github.com/angarce25/centro-deportivo-front.git
   ```

2. **Clonar el Repositorio del backend**

   ```bash
   git clone https://github.com/carlaprimola/centro-deportivo-back.git
   ```

3. **Instalar las dependencias**

   ```bash
   npm install
   ```

4. **Iniciar el cliente**

   ```bash
   npm run dev
   ```

5. **Configurar la base de datos** según las instrucciones proporcionadas.

<h4 id="version-control">Control de Versiones</h4>
<p><a href="#"><img src="https://img.shields.io/badge/git%20-%23F05033.svg?&amp;style=for-the-badge&amp;logo=git&amp;logoColor=white&amp;labelColor=101010" alt="Git"></a>
<a href="#"><img src="https://img.shields.io/badge/github%20-%23121011.svg?&amp;style=for-the-badge&amp;logo=github&amp;logoColor=whit&amp;logoColor=white&amp;labelColor=101010" alt="Github"></a></p>

# Ramas de Git
   ![Badge en Desarollo](https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green)

| RAMA   | Descripción                                                                            |
| ------- | -------------------------------------------------------------------------------------- |
| main    | Rama principal. Contiene los resultados finales.                                       |
| develop | Rama para desarrollos en progreso.                                                    |
| origin/feature/auth | Rama para gestión de token y registro de usuario, inicio de sesión |
| origin/feature/admin-dash | Rama para integración de token con las funcionalidades de administración |
| origin/feature/footer | Rama para la UI del pie de página |
| origin/feature/header | Rama para la UI del encabezado y funcionalidades de contacto |
| origin/feature/sidebar | Rama para la UI del sidebar de administrador y usuario |
| origin/feature/design | Rama de diseño general para estilos de componentes |
| origin/feature/form-player  | Estilización y funcionalidad del formulario de jugador |
| origin/feature/forms | Estilización y funcionalidad de los formularios de registro e inicio de sesión de usuario |
| origin/feature/home | Rama de UI para la página principal |
| origin/feature/merchandising | UI del merchandising sin iniciar sesión |
| origin/feature/new-player-form-integration | Rama de integración del formulario de jugador |
| origin/feature/order-users  | Rama para la UI de compra de usuario |
| origin/feature/players | Funcionalidades de administración para ver jugadores |
| origin/feature/products | Vista administrativa para pedidos de productos |
| origin/feature/resources | Recursos UI para componentes generales |
| origin/feature/sidebar | UI y funcionalidad para el sidebar |
| origin/feature/terms-and-conditions | UI para los términos y condiciones bajo la LOPD |
| origin/feature/user-profile | UI y funcionalidades para el perfil del usuario |
| origin/feature/users-and-players-view | UI vinculada de usuario y jugador |
| origin/feature/orders-detail-view | Vista detallada de pedidos de productos |
| origin/feature/order-pdf | Adjuntar PDF a la UI de pago de productos |
| origin/readme | Rama de modificaciones del README |
| origin/test/e2e | Rama de pruebas end-to-end del frontend |
| origin/chore/security-sanitization | Funcionalidades extra de seguridad en la UI |
| origin/security/decode| Rama de verificación de token en la UI |

# Planificación

- Planificación de tareas en

 Trello
- Standups diarios
- Sprints
- Todos por uno.

# Nuestro Equipo

- Carla Escobar (https://github.com/carlaprimola)
- Leandra Montoya (https://github.com/leamontoya19)
- Andrea García (https://github.com/angarce25)
- Fiorella Sandoval (https://github.com/FiorellaSF)
- Alvaro González (https://github.com/agt1984)
- Isaac García Adjuntar (https://github.com/Isarok)
- Abelardo Acosta (https://github.com/Moriarty369)

## Contribuir

Para contribuir a este proyecto, siga estos pasos:

1. Hacer un fork del repositorio.
2. Crear una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realizar sus cambios y hacer commit de ellos (`git commit -am 'Agregar nueva funcionalidad'`).
4. Subir sus cambios al repositorio (`git push origin feature/nueva-funcionalidad`).
5. Crear una nueva solicitud de Pull.
6. El equipo de desarrollo será notificado sobre la solicitud.

## Licencia

Este proyecto está bajo licencia. Para más detalles, consulte el archivo LICENSE.

---
```
