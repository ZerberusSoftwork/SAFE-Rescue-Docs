

<p align="left">
  <img src="./captures/SRCover.png" alt="Portada SAFE Rescue" width="900px">
</p>

*Gestión eficiente y rápida de incidentes en situaciones de emergencia.*

## Índice

- [Visión](#visión)
- [Problema que aborda](#problema-que-aborda)
- [Arquitectura](#arquitectura)
- [Estado Actual](#estado-actual)
- [Plataformas Compatibles](#plataformas-compatibles)
- [Modelo de Datos (MER)](#mer-actualizado)
- [Documentación Funcional](#documentación)
- [Prototipos](#mockups--prototipo)
- [Capturas del Sistema](#capturas-del-sistema)
- [Stack Tecnológico](#stack-tecnológico)
- [Resumen Técnico](#resumen-técnico)
- [Licencia](#licencia)

---

## Visión

SAFE RESCUE nace con el objetivo de desarrollar una solución tecnológica escalable y estructurada para la gestión de incidentes, coordinación operativa y toma de decisiones en tiempo real.

El proyecto busca integrar aplicaciones móviles, una plataforma web administrativa y un backend centralizado dentro de un mismo ecosistema tecnológico, permitiendo eficiencia, trazabilidad y crecimiento sostenible.

---

## Problema que aborda

La gestión de incidentes críticos suele presentar desafíos como:
- Falta de centralización de información
- Tiempos de respuesta elevados
- Baja trazabilidad de eventos
- Coordinación deficiente entre actores involucrados

SAFE RESCUE propone un ecosistema tecnológico integrado que permite registrar, monitorear y gestionar incidentes en tiempo real mediante aplicaciones web y móvil y un backend basado en microservicios.

---

## Arquitectura

El sistema sigue una arquitectura modular compuesta por:

- Backend API (capa central de servicios)
- Plataforma Web (panel administrativo y operativo)
- Aplicación Móvil (interacción en campo y reporte ciudadano)
- Base de datos SQL relacional

<p align="left">
  <img src="./captures/arqdiagram.png" alt="arqdiagram" width="1000px">
</p>


---

## Estado Actual

- ✅ Backend funcional con endpoints principales implementados
- ✅ Aplicación web en desarrollo / pruebas
- ✅ Aplicación móvil en desarrollo / pruebas
- ⚠️ Proyecto en fase de evolución y mejora estructural
- 🚧 Próxima iteración: refactorización y nueva versión del backend

---

## Plataformas Compatibles

- Navegadores modernos (Chrome, Edge, Firefox)
- Android
- Sistemas compatibles con Node/Java runtime (según backend)

---

## MER Actualizado

El Modelo Entidad-Relación contempla actualmente:
<p align="left">
  <img src="./captures/mercompleto.png" alt="mercompleto" width="1000px">
</p>


MER Servicio de Registros
<p align="left">
  <img src="./captures/mer1.png" alt="mer1" width="600px">
</p>

MER Servicio de Geolocalización
<p align="left">
  <img src="./captures/mer2.png" alt="mer2" width="600px">
</p>

MER Servicio de Perfiles
<p align="left">
  <img src="./captures/mer3.png" alt="mer3" width="1000px">
</p>

MER Servicio de Incidentes
<p align="left">
  <img src="./captures/mer4.png" alt="mer4" width="600px">
</p>

MER Servicio de Comunicaciones
<p align="left">
  <img src="./captures/mer5.png" alt="mer5" width="800px">
</p>

MER Servicio de Donaciones
<p align="left">
  <img src="./captures/mer6.png" alt="mer6" width="800px">
</p>

---

## Documentación

Se desarrolló la documentación necesaria para un correcto levantamiento y validación de requisitos.

- Historias de usuario
- Story Points
- Matriz de trazabilidad de requisitos
- Plan de pruebas
- Informe de proyecto academico

---

## Prototipos

Diseños iniciales y prototipos de interfaz:




### SAFE Rescue Web

Prototipo v1 web:
https://www.figma.com/proto/qvxqCOfDHKLOc5PZsLuMDS/Proyecto-cerberus?node-id=0-1&t=sNtcV2KTPSNAvrMV-1

Prototipo v2 web:
https://www.figma.com/proto/qvxqCOfDHKLOc5PZsLuMDS/Proyecto-cerberus?node-id=270-2&t=qFhMzO30pOFWKobh-1

Prototipo v3 web:
https://www.figma.com/proto/tIkJhj3iBQ6JOv6lHWBEg1/SAFE-Rescue-F4?node-id=2-4210&t=zxsgNenAv1z5YUlP-1

---
Pantalla de inicio prototipo v1
<p align="left">
  <img src="./captures/prototipow0.png" alt="prototipow0" width="1200px">
</p>


Pantalla de mapa prototipo v2
<p align="left">
  <img src="./captures/prototipow1.png" alt="prototipow1" width="1200px">
</p>

<p align="left">
  <img src="./captures/prototipow2.png" alt="prototipow2" width="600px">
  <img src="./captures/prototipow3.png" alt="prototipow3" width="600px">
</p>

---
### SAFE Rescue Movil


Prototipo v1 movil:
https://www.figma.com/proto/qvxqCOfDHKLOc5PZsLuMDS/Proyecto-cerberus?node-id=322-506&t=qFhMzO30pOFWKobh-1

Prototipo v2 movil:
https://www.figma.com/proto/tIkJhj3iBQ6JOv6lHWBEg1/SAFE-Rescue-F4?node-id=213-913&t=zxsgNenAv1z5YUlP-1

---

Pantallas Prototipo v1 movil:
<p align="left">
  <img src="./captures/prototipom1.png" alt="prototipom1" width="800px">
</p>


---

## Capturas del Sistema

### SAFE Rescue Web

Pantalla de inicio
<p align="left">
  <img src="./captures/inicio.png" alt="inicio" width="1000px">
</p>


Pantalla de registro

  <img src="./captures/registro.png" alt="registro" width="1000px">
</p>


Pantalla de perfil
<p align="left">
  <img src="./captures/perfil1.png" alt="perfil1" width="1000px">
</p>


Pantalla de mapa e incidentes

<p align="left">
  <img src="./captures/mapa2.png" alt="mapa2" width="1000px">
</p>


### SAFE Rescue Movil


Pantallas de inicio y mapa
<p align="left">
  <img src="./captures/iniciom.png" alt="iniciom" width="320px">
  <img src="./captures/mapam.png" alt="mapam" width="320px">
</p>


Pantalla de incidentes
<p align="left">
  <img src="./captures/incidentem3.png" alt="incidentem3" width="320px">
  <img src="./captures/incidentem.png" alt="incidentem" width="320px">
  <img src="./captures/incidentem2.png" alt="incidentem2" width="322px">
</p>

Menu lateral y pantalla mi Merfil
<p align="left">
  <img src="./captures/menulateralm.png" alt="menulateralm" width="320px">
  <img src="./captures/perfilm.png" alt="perfilm" width="320px">
</p>

### SAFE Rescue Backend

SAFE Rescue launcher v1
<p align="left">
  <img src="./captures/srbacklauncher.png" alt="srbacklauncher" width="150px">
</p>

Menu principal
<p align="left">
  <img src="./captures/srlauncherlist.png" alt="srlauncherlist" width="1000px">
</p>

Menu de inicio Backend
<p align="left">
  <img src="./captures/srlauncherstart.png" alt="srlauncherstart" width="1000px">
</p>

Menu de detención Backend
<p align="left">
  <img src="./captures/srlauncherstop.png" alt="srlauncherstop" width="1000px">
</p>


Menu de estado Backend
<p align="left">
  <img src="./captures/srlauncherstatus.png" alt="srlauncherstatus" width="1000px">
</p>


---


## Stack Tecnológico

### Backend
- Java 
- Springboot
- API REST
- Base de datos SQL
- Node.js

### Frontend Web
- React
- TypeScript 
- Bootstrap
- CSS Modules

### Mobile
- Kotlin
- Jetpack Compose
- Android SDK

### Otros
- Git & GitHub
- XAMPP
- SQL Developer
- Figma

---

## Resumen Técnico

SAFE RESCUE está diseñado bajo principios de:

- Modularidad
- Separación de responsabilidades
- Escalabilidad progresiva
- Seguridad en autenticación
- Estructura preparada para versionado

El proyecto se mantiene público únicamente con fines de portafolio y evaluación técnica.

---

## Licencia


Copyright © 2024–2026 SAFE Rescue Project.

All rights reserved.

This repository is published for portfolio and evaluation purposes only.  

No commercial use, redistribution, or derivative works are permitted without explicit permission from the original contributors.
