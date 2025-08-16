# Proyecto: Sistema de Control de Ventas para un Restaurante

## 1. Introducción  
El proyecto consiste en el desarrollo de un sistema básico para controlar las ventas en un restaurante.  
La finalidad es facilitar el registro de productos, la realización de ventas y la generación de reportes simples.  
El sistema está pensado para ser usado por el administrador o meseros del restaurante, permitiendo una gestión más organizada y eficiente.  

---

## 2. Tecnologías utilizadas  

- **HTML5** → Para la estructura de las páginas.  
- **CSS3** → Para los estilos y diseño visual.  
- **JavaScript** → Para validaciones básicas y cálculos en la interfaz.  
- **Java** → Para la lógica principal del sistema (manejo de productos y ventas).  
- **Archivos de texto (.txt)** → Para guardar los datos de manera sencilla (productos y ventas).  

> (Opcional: Se puede usar **MySQL con conexión JDBC** si se desea algo más avanzado).  

---

## 3. Entorno de trabajo  

- Editor para Java: **NetBeans** (o **IntelliJ IDEA**).  
- Editor para HTML/CSS/JS: **Visual Studio Code**.  
- **Java Development Kit (JDK):** Versión 17 o superior.  
- Sistema operativo: **Windows o Linux**.  

---

## 4. Tipo de Base de Datos  

- **Opción sencilla:** Archivos de texto (`productos.txt`, `ventas.txt`).  
  Cada vez que se registra un producto o una venta, se guarda la información en un archivo.  

- **Opción avanzada (opcional):** Base de datos **MySQL** conectada con Java mediante JDBC.  

---

## 5. Librerías utilizadas  

- **Java estándar:** Para manejar archivos (`BufferedWriter`, `BufferedReader`).  
- **JavaScript:** Para cálculos y validaciones en formularios.  
- No se utilizarán frameworks avanzados para mantenerlo simple.  

---

## 6. Área del proyecto  

El área principal del proyecto es **Logística**, enfocada en la gestión y organización de ventas en un restaurante.  
Además, se plantea una extensión opcional con IA para realizar predicciones simples de ventas futuras, usando datos históricos almacenados en archivos o base de datos.  

- **Logística:** Control de productos y ventas.  
- **IA (opcional):** Predicción de ventas diarias o semanales con cálculos básicos.  

---

## 7. Funcionalidades principales  

- **Login:** Acceso del administrador o mesero.  
- **Gestión de productos:** Agregar, editar y eliminar productos.  
- **Registro de ventas:** Seleccionar productos, cantidades y calcular total.  
- **Reportes:** Ventas realizadas, total del día.  

---

## 8. Diagrama de información (BD - IU - LN)  

**Explicación del diagrama:**  

- **Interfaz de Usuario (IU):** Formularios en HTML para login, registro de productos y ventas.  
- **Lógica de Negocio (LN):** Clases en Java que controlan el registro de productos y ventas.  
- **Base de Datos (BD):** Archivos de texto (o MySQL) donde se guarda la información.  

---

## 9. Diagrama con IA opcional  

Este diagrama muestra cómo se puede integrar un módulo opcional de **IA** para predecir ventas futuras usando datos del historial.  

---

## 10. Conclusión  

Este proyecto es una solución sencilla y funcional para la gestión de ventas en un restaurante, ideal para estudiantes que están iniciando en programación.  
Permite aplicar conceptos básicos de **Java, JavaScript y HTML**, además de reforzar el manejo de archivos o bases de datos.

## Integrantes
Juan Diego Torres Castro 
Ronald Gutierrez 
