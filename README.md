# S2.01-Ex1-Estructura-de-dades---MySQL-Nivel2
# Sistema de Base de Datos para Plataforma de Videos

## 📄 Descripción - Ejercicio

Este proyecto implementa un esquema de base de datos relacional para una plataforma de compartición de videos similar a YouTube. La base de datos incluye tablas para gestionar usuarios, videos, etiquetas, listas de reproducción, canales y varias características de interacción como comentarios, reacciones y suscripciones. Permite un ecosistema completo de plataforma de video con características sociales.

El esquema de la base de datos admite:
- Gestión y autenticación de usuarios
- Carga de videos y gestión de metadatos
- Etiquetado y categorización de contenido
- Suscripciones a canales
- Reacciones a videos y comentarios (me gusta/no me gusta)
- Creación y gestión de listas de reproducción
- Relaciones entre videos y etiquetas

## 💻 Tecnologías utilizadas

- SQL (MySQL/MariaDB)
- Java (JPA/Hibernate para interacción con la base de datos)
- Maven (para gestión de dependencias)
- Eclipse IDE

## 📋 REQUISITOS

Para ejecutar este proyecto, necesitas:
- Kit de Desarrollo de Java (JDK) 8 o superior
- Servidor de base de datos MySQL/MariaDB
- Eclipse IDE o IDE similar para Java
- Maven 3.6 o superior

## 🛠️ Instalación

1. Clonar el repositorio:
   ```
   git clone: https://github.com/MaraMarchello/S2.01-Ex1-Estructura-de-dades---MySQL-Nivel2.git
   ```

2. Importar el proyecto a Eclipse:
   - Abrir Eclipse
   - Seleccionar Archivo > Importar > Proyecto Maven Existente
   - Navegar al directorio del proyecto y seleccionarlo
   - Hacer clic en Finalizar

3. Configurar la base de datos:
   - Crear una nueva base de datos en MySQL/MariaDB
   - Actualizar las propiedades de conexión a la base de datos en la configuración de la aplicación

4. Inicializar la base de datos:
   - Ejecutar los scripts de esquema de base de datos para crear las tablas
   - Ejecutar los scripts de datos de ejemplo para poblar la base de datos con datos de prueba

## ▶️ Implementación

1. Iniciar el servidor MySQL/MariaDB
2. Ejecutar la aplicación desde Eclipse o usando Maven:
   ```
   mvn clean install
   mvn exec:java
   ```
3. La aplicación se conectará a la base de datos y estará lista para su uso

## 🌐 DESPLIEGUE

Para desplegar este proyecto en un entorno de producción:

1. Configurar un servidor de base de datos de producción
2. Configurar la aplicación con credenciales de base de datos de producción
3. Construir la aplicación:
   ```
   mvn clean package
   ```
4. Desplegar el archivo JAR/WAR resultante en tu servidor de aplicaciones
5. Ejecutar los scripts de esquema en tu base de datos de producción

## 🤝 Contribución

Si deseas contribuir a este proyecto:

1. Haz un fork del repositorio
2. Crea una rama de características (`git checkout -b feature/caracteristica-asombrosa`)
3. Haz commit de tus cambios (`git commit -m 'Añadir alguna característica asombrosa'`)
4. Haz push a la rama (`git push origin feature/caracteristica-asombrosa`)
5. Abre una Solicitud de Extracción (Pull Request)
