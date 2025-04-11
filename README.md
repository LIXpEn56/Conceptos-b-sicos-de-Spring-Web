
UNIVERSIDAD AUTÓNOMA DE CAMPECHE

	FACULTAD DE INGENIERÍA

	INGENIERO EN SISTEMAS COMPUTACIONALES





ALUMNO(A): 			          SANCHEZ RAMIREZ SANDRA LIZETTE

SEMESTRE: 			          8VO 


UNIDAD DE APRENDIZAJE:	  TEMAS SELECTOS DE PROGRAMACIÓN


PROFESOR  :   JOSE AGUILAR CANEPA

# LoginApp - Aplicación de Inicio de Sesión con Spring Boot

Esta es una aplicación web básica desarrollada con **Spring Boot** y **Thymeleaf** que permite a los usuarios iniciar sesión mediante un formulario web. Si las credenciales son correctas, se muestra una pantalla de bienvenida; en caso contrario, se muestra un mensaje de error en el formulario.

---

## Características

- Formulario de inicio de sesión en `/inicio`
- Validación de usuario y contraseña
- Redirección a una página de bienvenida si el inicio es exitoso
- Mensaje de error si las credenciales son incorrectas
- Uso de Thymeleaf como motor de plantillas

---

## Estructura del Proyecto
### 1.   `User.java (modelo)` Clase que representa a un usuario con sus credenciales básicas (usuario y contraseña). Es utilizada como objeto de transferencia de datos (DTO) en los formularios.
![image](https://github.com/user-attachments/assets/2384693e-aded-480d-9d37-ab25dc681b99)

### 2.   `LoginController.java ` (controlador) Controlador que maneja las rutas /inicio tanto en GET como POST.
Se encarga de:
- Mostrar el formulario de login.
- Validar las credenciales.
- Redirigir según el resultado.
  
![image](https://github.com/user-attachments/assets/bdb5fc69-707b-42ea-b98f-93d0ea81091d)

 # Archivos HTML (Thymeleaf)
### `login.html`
Formulario para que el usuario ingrese sus datos. Incluye campos de usuario y contraseña, y muestra un mensaje si el login falla.

### `home.html`
Página de bienvenida mostrada solo si el login fue exitoso.

# Credenciales de prueba

#### Usuario: admin

#### Contraseña: 1234





