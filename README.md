# 🚗 PARKZONE - Sistema de Gestión de Parqueaderos

**PARKZONE** es una aplicación web backend/full-stack diseñada para la administración eficiente y control operativo de estacionamientos. Permite gestionar el flujo de vehículos en tiempo real (entradas/salidas), control de usuarios con autenticación y visualización de cupos disponibles.

---

### 🛠️ Tecnologías Utilizadas

* **Backend:** Java ☕, Spring Boot, Spring MVC, Spring Data JPA / Hibernate
* **Base de Datos:** MySQL
* **Frontend / Vistas:** JSP (JavaServer Pages), HTML5, CSS3, JavaScript
* **Gestor de Dependencias:** Apache Maven
* **Control de Versiones:** Git & GitHub

---

### ✨ Funcionalidades Principales

* 🔐 **Autenticación y Seguridad:** Registro, inicio de sesión y gestión de sesiones de usuarios/administradores.
* 🚘 **Control Vehicular:** Registro de ingreso y salida de vehículos desde módulos interactivos (incluyendo soporte para lectura/scanner).
* 📊 **Gestión de Estacionamiento:** Monitoreo y control del estado de ocupación del parqueadero.

---

### 🚀 Configuración y Ejecución Local

1. **Requisitos previos:**
   * Java JDK 17 o superior
   * Maven 3.x
   * Servidor MySQL en ejecución

2. **Pasos para clonar y ejecutar:**
   ```bash
   # Clonar el repositorio
   git clone [https://github.com/danielcuartas08/Parkzoneweb.git](https://github.com/danielcuartas08/Parkzoneweb.git)

   # Entrar al directorio
   cd Parkzoneweb

   # Ejecutar la aplicación con Maven
   ./mvnw spring-boot:run
