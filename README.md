# Chat

## Chat multiusuario con login.

Para este apartado de la prueba se plantea realizar un login para poder iniciar sesion y comenzar a utilizar el chat
en la captura se muestra como es es login de aplicación
![image](https://user-images.githubusercontent.com/66144899/127413305-6ed63415-7602-4f2d-bb9d-b66d221fd33d.png)

Ahora se muestra el codigo para poder iniciar sesión el cual esta implementado con Angular
![image](https://user-images.githubusercontent.com/66144899/127413396-fdefe5a6-77a5-4a43-98e3-77025d46e372.png)

Con ese codigo podemos validar los campos para poder iniciar sesión, ademas si deseamos registrarnos igualmente lo podemos hacer

## 1.- Registro de un nuevo usuario

Se muestra la pagina de registro que se va utilizar donde solo se pide el correo  y una contraseña
![image](https://user-images.githubusercontent.com/66144899/127413635-7d99f128-8cb4-46f3-8e2a-5cce59950de3.png)

El codigo que se uso para la implementación del registro es el siguiente
![image](https://user-images.githubusercontent.com/66144899/127413728-b45b931c-8219-477f-8601-8e11a02ea624.png)

Todo esto se almacena el firebase 
en la imagen se muetsra los uaurios que podran accedero se regitraron

![image](https://user-images.githubusercontent.com/66144899/127413831-f428ed6c-94fa-475b-b8a0-4613c7d1bb48.png)

## 2.- Almacenamiento en la base de datos los mensajes

En la siguiente imagen se muestra la pagina donde podran interactuar los usuario enviando imagenes
![image](https://user-images.githubusercontent.com/66144899/127413990-22bcfc2f-98b7-4e13-88b0-2a6c4be9bb31.png)

los mensajes seran encriptados gracias a un codigo de encriptacion
Acontinuacion se muestra como los mensajes son encriptados en la base de datos

![image](https://user-images.githubusercontent.com/66144899/127414084-fd1d4414-9e36-4c12-ad0c-c2e1a737d68a.png)

El codigo para lel chat es el siguiente:
![image](https://user-images.githubusercontent.com/66144899/127414289-2e040530-bcd5-41c8-8e8e-5aeb305084fa.png)


## 3.- Imagenes
Para poder compartir imagenes se utilizo es Storage de Firebase el cual va almacenar las imagenes.
Para podoer compartir las imagenes se tendra te utilizar el siguiente menú donde se va poder escoger las imagenes y se podran guardar en el Storage

![image](https://user-images.githubusercontent.com/66144899/127414376-2f099c52-bcb2-4f86-83b4-81134ad03a54.png)

El codigo para el control de la imagenes es el siguiente:
![image](https://user-images.githubusercontent.com/66144899/127414446-2639f01c-219e-4e87-a150-98874f0ef162.png)

Cabe recalcar que despues de guardar en el Storage se procede a guardar en la coleccion de messages con un codigo único.
A continuacion se muestra las imagenes que se almacenan en firebase

![image](https://user-images.githubusercontent.com/66144899/127414663-5c0a01ff-12ff-4017-b09d-708553ffff3d.png)


