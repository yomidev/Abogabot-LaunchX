# Abogabot Launch X
## Práctica Módulo 1 (Frontend)
Se requiere realizar un sistema para un grupo de abogados en el cual se permita la automatización al
seguimiento de los casos y demandas legales que se van a atender.
Por lo parte del cliente el sistema debe de permitir ingresar la información correspondiente al caso legal;
permitir realizar el pago correspondiente a través del sistema y por último tener un seguimiento del estatus de su caso y/o demanda

## Toma de Requerimientos 
- Nombre del proyecto: Abogabot
- Usuarios finales: Abogados y Clientes

**Requerimientos para el sistema final que usaran los Abogados**

- Página web en donde se muestre la información correspondiente de los servicios que se ofrecen
- Formulario para registro de casos de los clientes
- Agregar forma de pago dentro de la página 
- Interfaz de administración para los casos y las demandas de los Clientes
- Recibir notificaciones cada vez que llegue se registre un casos
- Ver los detalles del caso, tanto la información ingresada por el cliente (esto se debe de poder exportar a un documento de Word) y la información del pago correspondiente
- El sistema debe de permitir actualizar el estatus de la demanda así como de poder realizar comentarios sobre la misma
- Poder visualizar dentro del dashboard el total de ingresos percibidos (Una opción seria también permitir realizar reportes de esto)

**Requerimientos para el sistema final que usaran los clientes del despacho**

- Visualizar pagina web informativa
- Formulario para poder registrar los datos de su caso o demanda
- Poder realizar el pago correspondiente de honorarios
- Recibir notificaciones vía correo electrónico sobre el estatus de su caso
- Una vez que el cliente realiza el registro de su demanda, se debe de crear una cuenta en el sistema para que pueda llevar el seguimiento de sus casos
- Una vez que el cliente tiene una cuenta en la plataforma, desde ahí puede dar de alta algún otro caso

**Observaciones a considerar**

- Se debe de considerar el diseño responsive para que pueda ser accesible desde cualquier dispositivo
- El sistema deberá de validar si ya existe un registro a través del correo electrónico
- Si el registro de la persona ya existe, lo que se registro en el formulario se deberá de asignar a la cuenta existente; esto para evitar registros repetidos dentro del sistema y garantizar la integridad de la información

### Buyer persona
**Buyer Persona (Abogado)**
![Buyer Persona Abogado](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/BuyerPersona_Abogado.jpg?raw=true)
- Visualizar Buyer Persona Abogado (PDF)
    Click ***[here](https://github.com/yomidev/Abogabot-LaunchX/blob/main/pdf/Buyer%20Persona%20Abogado.pdf)***

**Buyer Persona (Cliente)**
![Buyer Persona Cliente](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/BuyerPersona_Cliente.jpg?raw=true)
- Visualizar Buyer Persona Cliente (PDF)
    Click ***[here](https://github.com/yomidev/Abogabot-LaunchX/blob/main/pdf/Buyer%20Persona%20Cliente.pdf)***


## Publico Objetivo
![Publico Objetivo](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/Target_Audience.png?raw=true)

## Diseño UX
### Wireframe Desktop (Landing Page)
![Esquema PT 1](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/wireframe/Wireframes.png?raw=true)
**Ver Wireframes individuales** [click here](https://github.com/yomidev/Abogabot-LaunchX/tree/main/img/wireframe)

### Wireframe Mobile (Landing Page)
![Esquema PT 1](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/UX_Mobile/Wireframes.png?raw=true)
**Ver Wireframes individuales** [click here](https://github.com/yomidev/Abogabot-LaunchX/tree/main/img/UX_Mobile)

### Wireframe Desktop (Admin Site)
![Esquema PT 1](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/Wireframe%20Plataforma/Wireframe_admin.jpg?raw=true)
**Ver Wireframes individuales** [click here](https://github.com/yomidev/Abogabot-LaunchX/tree/main/img/Wireframe%20Plataforma)

## Diseño UI
### Diseño en Figma
Para desarrollar el diseño UI se utilizo la herramienta conocida como Figma;
para el diseño se utilizo un color morado azulado, que nos indica elegancia y un color amarillo opaco.
(Es mi primera vez usando Figma).
- Algunas capturas del diseño
![Img1](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/UI/Principal.png?raw=true)
![Img2](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/UI/Formulario.png?raw=true)
![Img3](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/UI/Pago.png?raw=true)
![Img4](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/UI/Login.png?raw=true)
![Img5](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/UI/Mobile.png?raw=true)
![Img6](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/UI/Dashboard.png?raw=true)
![Img7](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/UI/Resumen%20de%20Casos.png?raw=true)
![img8](https://github.com/yomidev/Abogabot-LaunchX/blob/main/img/UI/Mobile%20admin.png?raw=true)
- El Diseño completo se puede visualizar a través del siguiente enlace
- [Diseño Figma](https://www.figma.com/file/mlecmuzNaRuAAgv5vLPZ8P/Abogabot?node-id=0%3A1)