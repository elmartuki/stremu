DEMO: https://stremu.netlify.app/


# 🎮 StremuGames

Bienvenido al repositorio de **StremuGames**.

> **🚀 Ver Proyecto Online:** [https://stremugames.vercel.app/](https://stremugames.vercel.app/)

---

## 📂 Estructura del Proyecto

El proyecto está organizado en dos carpetas principales dentro de la raíz:

* `back/`: Código del servidor (API, Base de Datos).
* `front/`: Código del cliente (React/Vite).

---

## 🛠️ Guía de Instalación Local

Sigue estos pasos para levantar el proyecto en tu computadora.

### 1️⃣ Configuración del Frontend

1.  **Navegar a la carpeta:**
    Abre tu terminal y entra en el directorio del frontend:
    ```bash
    cd front
    ```

2.  **Configurar Variables de Entorno:**
    Busca el archivo `.env.example` y cámbiale el nombre a `.env`.

3.  **Instalar Dependencias:**
    Ejecuta el siguiente comando para descargar las librerías necesarias:
    ```bash
    npm i
    ```

4.  **Iniciar el Proyecto:**
    Levanta la aplicación en modo desarrollo:
    ```bash
    npm run dev
    ```

### 2️⃣ Configuración del Backend

Para que la aplicación funcione completa (login, base de datos), también debes levantar el servidor en una **nueva terminal**:

1.  **Navegar a la carpeta:**
    ```bash
    cd back
    ```

2.  **Configurar Variables de Entorno:**
    Renombra el archivo `.env.example` a `.env` y configura tus credenciales.

3.  **Instalar y Ejecutar:**
    ```bash
    npm i
    npm run dev
    ```
