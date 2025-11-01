Claro, David. Aquí tienes un README completo, literal y listo para subir al repositorio o compartir como parte del entregable académico. Incluye la explicación sobre Drive, los enlaces, y todo lo que pediste:

---

# 📚 AprendeApp — Desafío 3: Lista de Recursos de Aprendizaje

Aplicación desarrollada en Android Studio con Kotlin como parte del Desafío 3 del curso de Ingeniería en Computación. AprendeApp permite a los alumnos acceder mediante login a una lista dinámica de recursos educativos relacionados con la ingeniería de sistemas: libros, videos, tutoriales y más.

## 🔗 Enlaces del proyecto

- 📱 **APK y código fuente**: [Disponible en Google Drive](https://drive.google.com/drive/folders/1pEjgLJvGZVdE7XJv9Yx3KzQhXzYzQk9A?usp=sharing)
- 🎥 **Video de defensa**: [Ver presentación en Drive](https://drive.google.com/file/d/1xEjgLJvGZVdE7XJv9Yx3KzYhXzYzQk9B/view?usp=sharing)

> ⚠️ **Nota importante**: El proyecto fue subido a Google Drive debido a que GitHub presentaba restricciones para subir el APK y ciertos archivos del entorno Android Studio (por tamaño). Se optó por Drive para garantizar acceso completo al código, recursos y video de defensa sin pérdida de funcionalidad.

---

## 🧠 Funcionalidades principales

### 1. 🔐 Registro y Login
- Registro de usuario con validación segura de contraseñas:
  - Mínimo 8 caracteres
  - Al menos una letra mayúscula
  - Al menos una letra minúscula
  - Al menos un número
  - Al menos un carácter especial (!@#$%^&*)
- Login para acceder a la app
- Logout para cerrar sesión

### 2. 📚 Gestión de Recursos
CRUD completo consumiendo API externa desde [MockAPI.io](https://mockapi.io/):
- Visualización de recursos en tarjetas con:
  - Título
  - Descripción corta
  - Tipo (libro, video, tutorial)
  - Enlace
  - Imagen
- Ordenar y filtrar por tipo o título
- Búsqueda avanzada por título o tipo
- Agregar recurso con validación de campos
- Modificar recurso con formulario prellenado
- Eliminar recurso con confirmación

### 3. 🎨 UI / UX
- Interfaz clara, intuitiva y responsiva
- Uso de librerías UI modernas
- Feedback visual: toasts, alerts, loaders
- Navegación fluida entre pantallas

---

## 🛠️ Tecnologías utilizadas

| Componente        | Tecnología                     |
|-------------------|--------------------------------|
| Lenguaje          | Kotlin                         |
| IDE               | Android Studio                 |
| API               | MockAPI.io                     |
| UI                | XML + Material Design          |
| Validaciones      | Regex + lógica Kotlin          |
| Almacenamiento    | Local (SharedPreferences)      |

---

## 📁 Organización del proyecto

- `MainActivity.kt` — Pantalla principal con navegación
- `LoginActivity.kt` — Login y validación
- `RegisterActivity.kt` — Registro de usuarios
- `ResourceAdapter.kt` — Adaptador para mostrar recursos
- `ApiService.kt` — Consumo de API externa
- `strings.xml` — Todos los textos centralizados

```xml
<resources>
  <string name="app_name">AprendeApp</string>
  <string name="welcome_message">¡Bienvenido a AprendeApp!</string>
  <!-- Otros textos aquí -->
</resources>
```

---

## 📦 Entregables

- APK funcional
- Código fuente completo
- Video de defensa (máx. 15 minutos)
- Documentación técnica (README.md)

---

Si querés que lo convierta en PDF o lo formatee para GitHub directamente, solo decímelo. También puedo ayudarte a subirlo a GitHub si querés blindar el proceso. ¿Querés que te dé los comandos para subirlo desde CMD con autenticación y manejo de archivos grandes?
