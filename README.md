<div align="center">

<!-- Cabecera con gradiente -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,16,18,20&height=200&section=header&text=Fall%20Detection%20System&fontSize=45&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Sistema%20Inteligente%20de%20Detección%20de%20Caídas&descSize=16&descAlignY=55" width="100%"/>

<!-- Badges con colores personalizados -->
<p>
  <img src="https://img.shields.io/badge/ESP32-IoT-1a4d7a?style=for-the-badge&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-Backend-2d5a7b?style=for-the-badge&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/Angular-Frontend-3d6a8c?style=for-the-badge&logo=angular&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-Database-1a4d7a?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-Cache-ff8c42?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Estado-En%20Desarrollo-ff8c42?style=flat-square&labelColor=1a4d7a"/>
  <img src="https://img.shields.io/badge/Equipo-7%20Desarrolladores-ff8c42?style=flat-square&labelColor=1a4d7a"/>
  <img src="https://img.shields.io/badge/Licencia-MIT-ff8c42?style=flat-square&labelColor=1a4d7a"/>
</p>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,14&height=4" width="80%"/>

### **ESTRUCTURA DEL PROYECTO**

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,14&height=4" width="80%"/>

</div>

<table align="center">
<tr>
<td width="50%" valign="top">

### **`📡 Device Layer`**
```yaml
device/
├── src/
│   ├── main.cpp
│   ├── acelerometro.cpp
│   ├── boton.cpp
│   └── red.cpp
└── platformio.ini
```
**Responsable:** Diego Argüelles  
**Stack:** ESP32, MPU6050, C++  
**Función:** Firmware y sensores IoT

</td>
<td width="50%" valign="top">

### **`⚙️ Backend Layer`**
```yaml
backend/
├── src/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   └── routes/
└── package.json
```
**Responsables:** Javier Gonzales, Diego Alonso  
**Stack:** Node.js, Express, PostgreSQL  
**Función:** API REST y gestión de datos

</td>
</tr>
<tr>
<td width="50%" valign="top">

### **`🎨 Frontend Layer`**
```yaml
frontend/
├── src/
│   ├── app/
│   ├── components/
│   ├── services/
│   └── environments/
└── angular.json
```
**Responsables:** Juan Carlos, Javier Sio  
**Stack:** Angular, TypeScript, Tailwind  
**Función:** Interfaz web y dashboard

</td>
<td width="50%" valign="top">

### **`📚 Documentation`**
```yaml
docs/
├── diagrams/
│   ├── arquitectura.md
│   └── flujo-caidas.md
└── manuals/
    ├── tecnico.md
    └── usuario.md
```
**Responsables:** Marta de Castro, Pedro Lourido  
**Stack:** Markdown, Diagramas  
**Función:** Documentación técnica

</td>
</tr>
</table>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=16,18&height=4" width="80%"/>

### **FLUJO DE TRABAJO GIT**

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=16,18&height=4" width="80%"/>

</div>

<table align="center">
<tr>
<td align="center" width="25%">

**🔵 Ramas Principales**

`main`  
*Producción estable*

`develop`  
*Desarrollo activo*

</td>
<td align="center" width="25%">

**🟠 Ramas de Tarea**

`feature/nombre-tarea`

Crear desde `develop`

</td>
<td align="center" width="25%">

**🔵 Pull Requests**

Revisión obligatoria

Aprobación del equipo

</td>
<td align="center" width="25%">

**🟠 Commits**

```
feat: nueva funcionalidad
fix: corrección de bug
docs: documentación
```

</td>
</tr>
</table>

> **Regla de Oro:** Todo cambio debe pasar por revisión de código antes de integrarse en `develop`

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,20&height=4" width="80%"/>

### **EQUIPO DE DESARROLLO**

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,20&height=4" width="80%"/>

</div>

<table align="center">
<tr>
<td align="center" width="33%">
<br>

**Diego Argüelles Fernández**  
`IoT & Sensores`  
<sub>ESP32 | Hardware | Firmware</sub>

</td>
<td align="center" width="33%">
<br>

**Javier Gonzales Rodríguez**  
`Backend | Deploy`  
<sub>API REST | Infraestructura</sub>

</td>
<td align="center" width="33%">
<br>

**Diego Alonso Loureiro**  
`Scrum Master | Database`  
<sub>PostgreSQL | Gestión</sub>

</td>
</tr>
<tr>
<td align="center" width="33%">
<br>

**Juan Carlos Lorenzo Villaar**  
`Frontend Logic`  
<sub>Angular | TypeScript</sub>

</td>
<td align="center" width="33%">
<br>

**Javier Sio**  
`UI/UX Design`  
<sub>Diseño | Experiencia Usuario</sub>

</td>
<td align="center" width="33%">
<br>

**Marta de Castro Vázquez**  
`Documentation | QA`  
<sub>Calidad | Testing</sub>

</td>
</tr>
<tr>
<td align="center" colspan="3">
<br>

**Pedro Lourido**  
`Extra Features | Support`  
<sub>Funcionalidades Adicionales | Apoyo al Equipo</sub>

</td>
</tr>
</table>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=14,16&height=4" width="80%"/>

### **INSTALACIÓN Y DESPLIEGUE**

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=14,16&height=4" width="80%"/>

</div>

<table align="center">
<tr>
<td width="33%" align="center">

### **Hardware Setup**

**ESP32 Configuration**

1. Abrir proyecto en `/device`
2. Configurar credenciales WiFi
3. Compilar y subir firmware
4. Verificar conexión MQTT

```bash
pio run --target upload
```

</td>
<td width="33%" align="center">

### **Backend Setup**

**API Server**

1. Navegar a `/backend`
2. Instalar dependencias
3. Configurar variables `.env`
4. Iniciar servidor

```bash
npm install
npm run dev
```

</td>
<td width="33%" align="center">

### **Frontend Setup**

**Web Application**

1. Abrir carpeta `/frontend`
2. Instalar paquetes
3. Configurar environment
4. Ejecutar aplicación

```bash
npm install
ng serve
```

</td>
</tr>
</table>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,16,18,20&height=100&section=footer" width="100%"/>

---

**Desarrollado con dedicación por el equipo Fall Detection System**  
*Tecnología al servicio de la seguridad y el cuidado*

</div>
