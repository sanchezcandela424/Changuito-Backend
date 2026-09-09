# 🍔 Changuito

## 🚀 Tecnologías Utilizadas

- **Java 21**
- **Spring Boot 3.4.5**
- **PostgreSQL**
- **Spring Data JPA**
- **Spring Security & OAuth2 (Google)**
- **JWT (JSON Web Tokens)**
- **MapStruct**
- **Lombok**
- **MercadoPago SDK**
- **OpenAPI (Swagger UI)**
- **Maven**

---

## ⚙️ Instalación y Ejecución

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/juli-ortega/buensabor-backend Back
   cd Back
   ```

2. **Configura las variables de entorno**
   - Copia `.env.example` a `.env` y completa los valores requeridos.

3. **Prepara la base de datos**
   - Crea una base de datos PostgreSQL y ajusta las credenciales en el archivo de configuración (`application.properties` o `.env`).

4. **Compila y ejecuta la aplicación**
   - En Linux/Mac:
     ```bash
     ./mvnw spring-boot:run
     ```
   - En Windows:
     ```bat
     mvnw.cmd spring-boot:run
     ```
