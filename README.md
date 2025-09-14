# Gestor de Presupuestos para Carpintería

Aplicación de escritorio local y multiplataforma para la gestión de presupuestos, diseñada para un carpintero profesional. Permite almacenar conceptos y precios, gestionar una base de datos de clientes y generar presupuestos en formato PDF de forma rápida y sin necesidad de conexión a internet.

---

## 🚀 Características Principales
* **Gestión Completa:** CRUD (Crear, Leer, Actualizar, Borrar) para Conceptos y Clientes.
* **Creación de Presupuestos:** Interfaz intuitiva para seleccionar clientes, añadir conceptos y calcular totales con IVA en tiempo real.
* **Búsqueda y Paginación:** Todas las listas están optimizadas para manejar grandes cantidades de datos.
* **Generación de PDF:** Exporta presupuestos con un diseño profesional, incluyendo el logo de la empresa.
* **Aplicación de Escritorio:** Empaquetada con Electron para funcionar como un programa nativo en Windows, sin dependencias externas ni necesidad de internet.

---

## 🛠️ Tecnologías Utilizadas
* **Backend:** Java 17, Spring Boot
* **Frontend:** Svelte, SvelteKit
* **Base de Datos:** SQLite
* **Empaquetado:** Electron
* **Generación de PDF:** OpenPDF

---

## 📸 Capturas de Pantalla

(Aquí es donde pondremos las imágenes de la aplicación)

**Gestor de Conceptos**
<img width="1882" height="1016" alt="Image" src="https://github.com/user-attachments/assets/55b14313-a0a4-42aa-802c-adee2117e22f" />
**Gestor de Clientes**
<img width="1912" height="1022" alt="Image" src="https://github.com/user-attachments/assets/67479c48-9ac6-4b3e-8044-1e895474aa2c" />
**Creación de un Presupuesto**
<img width="1917" height="1042" alt="Image" src="https://github.com/user-attachments/assets/f62e346f-9bb4-4dcc-9ad9-c8edbb0d947d" />

---

## ⚙️ Cómo Ejecutar en Desarrollo
Instrucciones detalladas para que otro desarrollador pueda ejecutar el proyecto.

### Backend (Java)
1.  Navegar a la carpeta `backend`.
2.  Ejecutar la aplicación usando un IDE o con el comando de Maven.

### Frontend (Svelte + Electron)
1.  Navegar a la carpeta `frontend`.
2.  Instalar dependencias: `npm install`.
3.  Ejecutar el servidor de desarrollo: `npm run dev`.
4.  En otra terminal, ejecutar Electron: `npm run electron:dev`.