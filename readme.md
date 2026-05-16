<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/2972/2972185.png" />

# 🚴 Online Bike Rental Management System

### Plataforma web de renta y administración de bicicletas 🚀

<p align="center">
  <b>Online Bike Rental Management System</b> es una plataforma desarrollada para gestionar el alquiler de bicicletas de forma eficiente, permitiendo a usuarios reservar bicicletas, consultar disponibilidad y administrar servicios de movilidad urbana.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/BikeRental-WebPlatform-2E8B57?style=for-the-badge">
  <img src="https://img.shields.io/badge/PHP-FullStack-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-Academic-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Online Bike Rental Management System** es un sistema web orientado a la gestión y renta de bicicletas, diseñado para automatizar reservas, administración de bicicletas y control de usuarios en plataformas de movilidad urbana.

El sistema fue desarrollado para:

- 🚴 Gestionar bicicletas
- 👥 Administrar usuarios
- 📅 Controlar reservas
- 📍 Gestionar estaciones
- 💳 Facilitar rentas
- 📊 Supervisar operaciones
- 🔐 Gestionar accesos
- 🌐 Optimizar movilidad urbana

---

# ✨ Características

## 🚴 Gestión de bicicletas

- 🚲 Registro de bicicletas
- 📍 Gestión de estaciones
- 🖼️ Carga de imágenes
- ⚙️ Control de disponibilidad
- 📋 Información detallada

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- ⚡ Activación y desactivación
- 📊 Administración centralizada

---

## 📅 Sistema de reservas

- 📆 Reservación de bicicletas
- ⏱️ Gestión de horarios
- 💳 Control de pagos
- ⚡ Confirmaciones rápidas
- 📋 Historial de rentas

---

## 📊 Panel administrativo

- 📈 Dashboard administrativo
- 🚴 Gestión de bicicletas
- 👥 Administración de usuarios
- 📅 Supervisión de reservas
- 🔐 Gestión de permisos

---

# 👨‍💼 Módulos del sistema

## 🚴 Bike Module

Este módulo permite gestionar todas las bicicletas registradas dentro del sistema.

### Funcionalidades:

- ➕ Registro de bicicletas
- 🛠️ Gestión de mantenimiento
- 📍 Administración de estaciones
- ⚙️ Control de disponibilidad
- 🖼️ Gestión de imágenes
- 📋 Información detallada

---

## 👤 User Module

Este módulo es utilizado por los clientes para acceder al sistema de renta.

### Funcionalidades:

- 🔐 Inicio de sesión
- 📄 Gestión de perfil
- 🚲 Reservar bicicletas
- 📅 Consultar historial
- 💳 Gestión de pagos

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal del sistema.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🚴 Supervisar bicicletas
- 📊 Dashboard del sistema
- 📅 Gestión de reservas
- 🔐 Administración general

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js" />
</p>

- HTML5
- CSS3
- Bootstrap
- JavaScript

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php" />
</p>

- PHP
- CRUD System
- Gestión de sesiones
- Arquitectura web

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Persistencia de datos
- Gestión de rentas

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- XAMPP / WAMP

---

# 📂 Estructura del proyecto

```bash
OnlineBikeRentalManagementSystem/
│
├── admin/                    # Panel administrativo
├── user/                     # Módulo usuario
├── bikes/                    # Gestión de bicicletas
├── assets/                   # Recursos frontend
├── database/                 # Scripts SQL
├── uploads/                  # Imágenes de bicicletas
├── includes/                 # Configuración y conexión
├── index.php                 # Página principal
├── login.php                 # Inicio de sesión
├── register.php              # Registro de usuarios
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 7+
- MySQL
- Apache
- XAMPP / WAMP
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/OnlineBikeRentalManagementSystem.git
```

---

## 2️⃣ Mover archivos

Copiar proyecto hacia:

```bash
xampp/htdocs/OnlineBikeRentalManagementSystem/
```

---

## 3️⃣ Crear base de datos

Crear base:

```bash
bike_rental_system
```

---

## 4️⃣ Importar SQL

Importar:

```bash
database/bike_rental_system.sql
```

---

## 5️⃣ Configurar conexión

Editar:

```bash
includes/config.php
```

Agregar:

```php
define('DB_HOST','localhost');
define('DB_USER','root');
define('DB_PASS','');
define('DB_NAME','bike_rental_system');
```

---

## 6️⃣ Ejecutar proyecto

Abrir:

```bash
http://localhost/OnlineBikeRentalManagementSystem/
```

---

# 📊 Funcionalidades principales

## 🚴 Gestión de bicicletas

- Registro de bicicletas
- Administración de disponibilidad
- Gestión de mantenimiento
- Control de estaciones

---

## 👥 Administración de usuarios

- Registro y autenticación
- Gestión de perfiles
- Roles administrativos
- Historial de rentas

---

## 📅 Gestión de reservas

- Reservas en tiempo real
- Control de horarios
- Historial de alquileres
- Confirmación automática

---

# 📸 Vista previa

## 🖥️ Interfaces del sistema

<div align="center">

### 🚴 Página principal
![Home](https://images.unsplash.com/photo-1485965120184-e220f721d03e?q=80&w=1200&auto=format&fit=crop)

### 🔐 Inicio de sesión
![Login](https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1200&auto=format&fit=crop)

### 🚲 Catálogo de bicicletas
![Bikes](https://images.unsplash.com/photo-1507035895480-2b3156c31fc8?q=80&w=1200&auto=format&fit=crop)

### 📅 Sistema de reservas
![Booking](https://images.unsplash.com/photo-1511994298241-608e28f14fde?q=80&w=1200&auto=format&fit=crop)

### 📊 Dashboard administrativo
![Dashboard](https://images.unsplash.com/photo-1460925895917-afdab827c52f?q=80&w=1200&auto=format&fit=crop)

### 👥 Gestión de usuarios
![Users](https://images.unsplash.com/photo-1521737604893-d14cc237f11d?q=80&w=1200&auto=format&fit=crop)

### ⚙️ Administración de bicicletas
![Admin](https://images.unsplash.com/photo-1517649763962-0c623066013b?q=80&w=1200&auto=format&fit=crop)

### 📍 Gestión de estaciones
![Stations](https://images.unsplash.com/photo-1508975551575-810f0d6e8d0d?q=80&w=1200&auto=format&fit=crop)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web full stack
- Gestión de movilidad urbana
- Bases de datos relacionales
- CRUD administrativos
- Sistemas de autenticación
- Arquitectura web
- Automatización de reservas

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Pagos electrónicos
- 📍 Geolocalización GPS
- 🚴 Rastreo de bicicletas
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por plataformas web, sistemas administrativos y soluciones de movilidad inteligente 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT orientado al aprendizaje y administración de sistemas de renta de bicicletas.

---

<div align="center">

### 🚴 Online Bike Rental Management System — movilidad inteligente y gestión eficiente 🚀

</div>
