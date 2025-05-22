# Proyecto Profe - Asilo de Ancianos Esperanza de Santa Ana

# Documentacion : https://deepwiki.com/AlexanderSiguenza/AsiloApp

El **Asilo de Ancianos Esperanza de Santa Ana** actualmente lleva los registros de sus pacientes, doctores e historial de citas en tablas de Excel, lo cual ocasiona pérdidas de información. Cada doctor maneja su propio archivo, y a menudo olvidan actualizarlo tras las citas. Debido a esta situación, solicitan una **aplicación móvil** que centralice el control de los registros. La aplicación permitirá:

1. Acceso a la aplicación mediante usuario y contraseña, con opción de autenticación a través de Gmail.
2. Funcionalidades para **crear**, **actualizar** y **ver**:
   - Pacientes
   - Doctores
   - Citas
3. Acceso a un historial de citas.

---

## Etapa 1: Configuración Inicial y Autenticación ✅

**Objetivo**: Establecer la base del proyecto y permitir el acceso seguro a la aplicación.

### Tareas

1. **Crear el proyecto** utilizando Expo y configurar el entorno de desarrollo.
2. **Configurar Firebase** para gestionar la autenticación de usuarios.
3. **Desarrollar las pantallas de autenticación**:
   - `LoginScreen`: Pantalla de inicio de sesión.
   - `RegisterScreen`: Pantalla de registro de nuevos usuarios.
4. **Implementar la lógica de autenticación** en el archivo `authService.js`, manejando los casos de inicio de sesión y registro mediante usuario/contraseña y Gmail.
5. **Configurar el AuthNavigator** para gestionar la navegación entre las pantallas de autenticación, permitiendo alternar entre el login y el registro.

**Estado**: ¡Etapa finalizada! ✅


---

## Etapa 2: Pantalla de Inicio y Navegación  ✅
Objetivo: Crear la pantalla principal y gestionar la navegación entre diferentes secciones de la aplicación.

Crear una pantalla principal (HomeScreen) que incluya opciones para acceder a las secciones de Pacientes, Doctores y Citas.
Implementar un menú o pestañas de navegación para facilitar el acceso a las diferentes secciones de la aplicación.
Configurar el AppNavigator:

Establecer un Stack.Navigator en el archivo AppNavigator.js para manejar la navegación entre la pantalla de inicio y las demás pantallas de la aplicación.
Asegurarse de que cada pantalla tenga su propio título y se muestre correctamente en la barra de navegación.

Estado: ¡Etapa finalizada! ✅


---

## Etapa Final ✅

Estado: ¡Etapa finalizada! ✅

---

# Login
<img src="https://github.com/AlexanderSiguenza/AsiloApp/blob/main/img/tarea1.jpg" alt="Descripción de la imagen" width="300" height="600">


# Registro
<img src="https://github.com/AlexanderSiguenza/AsiloApp/blob/main/img/tarea2.jpg" alt="Descripción de la imagen" width="300" height="600">


# Menu
<img src="https://github.com/AlexanderSiguenza/AsiloApp/blob/main/img/tarea6.jpg" alt="Descripción de la imagen" width="300" height="600">


# Pacientes
<img src="https://github.com/AlexanderSiguenza/AsiloApp/blob/main/img/tarea3.jpg" alt="Descripción de la imagen" width="300" height="600">


# Doctores
<img src="https://github.com/AlexanderSiguenza/AsiloApp/blob/main/img/tarea4.jpg" alt="Descripción de la imagen" width="300" height="600">


# Citas
<img src="https://github.com/AlexanderSiguenza/AsiloApp/blob/main/img/tarea5.jpg" alt="Descripción de la imagen" width="300" height="600">
