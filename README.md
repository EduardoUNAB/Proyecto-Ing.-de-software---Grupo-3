## Sistema FSM — Gestión de Instalaciones y Monitoreo Técnico

> **Proyecto de Ingeniería de Software I & II — Universidad Andrés Bello (UNAB)**  
> Grupo 3 · Sección · Profesor: Paulo Quinsacara Jofré

---

## Descripción

Sistema de **Field Service Management (FSM)** desarrollado para **FiNet Limitada** y **Cable Mágico Litoral**, empresas de telecomunicaciones por fibra óptica. El sistema centraliza y digitaliza la operación de órdenes de trabajo, el monitoreo de red en tiempo real y la gestión de clientes e inventario.

---

## Equipo de Desarrollo — Grupo 3

| Nombre | Rol |
|--------|-----|
| Abarca Vicente | Integrante |
| Chávez Fernando | Integrante |
| Cornejo Iosef | Integrante |
| Díaz Vicente | Integrante |
| Gálvez Matías | Integrante |
| Rojas Fernando | Integrante |
| Zepeda Eduardo | Jefe de grupo |

---

## Stack Tecnológico

| Capa | Tecnología |
|------|------------|
| Vista | SvelteKit + TypeScript + Tailwind CSS |
| Controlador | NestJS + TypeScript + Socket.io |
| Modelo | PostgreSQL + Prisma ORM |
| Almacenamiento de imágenes | Cloudinary |
| Despliegue Vista | Vercel |
| Despliegue Controlador + Modelo | Railway |
| Autenticación | JWT + bcrypt factor 12 |
| Monitoreo ONT | API SmartOLT |

---

## Entregas

| Entrega | Contenido principal |
|---------|---------------------|
| **Documento 0** | Análisis de la organización (FODA, Porter, Ishikawa, Pareto), levantamiento de procesos, requerimientos y casos de uso, estimación costo-beneficio, Carta Gantt y CVs del equipo |
| **Incremento 1** | Arquitectura (diagramas de componentes y despliegue), modelo de datos (MER / MR), diagramas de secuencia, árbol de navegación, presentación y video |
| **Incremento 2** | Diagramas de secuencia ampliados con nuevos casos de uso, árbol de navegación actualizado, planificación del sprint y presentación |

---

## Estructura del Repositorio

```
📦 Proyecto Ing. de Software - Grupo 3
├── 📂 Documento 0
│   ├── Grupo N3 - Documento 0.docx
│   ├── Grupo N3 - Presentación.pptx
│   ├── 📂 Diagramas de módulos de CU        (Módulos 1 a 9 — casos de uso extendidos)
│   ├── Análisis: FODA, Fuerza de Porter, Diagrama de Ishikawa, Diagrama Pareto
│   ├── Operación: Organigrama, Volumen Operativo Mensual, Distribución Carga Operativa
│   ├── Levantamiento de procesos Inicial.bpm
│   ├── Planillas: TablaESA_UR, Matriz de Requisitos vs CU, CartaGantt_FSM,
│   │              Estimación de costo - beneficio
│   ├── Aceptacion_Requerimientos.png
│   └── CVs del equipo (Cv_*.png)
├── 📂 Incremento 1
│   ├── Grupo N3 - Incremento 1.docx
│   ├── Presentación - Incremento 1.pptx
│   ├── Presentación - Incremento 1.mp4
│   ├── 📂 Diagramas de Secuencias - Vista Proceso
│   ├── Diagrama de componentes.png
│   ├── Diagrama de despliegue.png
│   ├── MERE_Finet.png
│   ├── MR Finet.docx
│   ├── Árbol de navegación.png
│   └── Grupo 3 - Organización de trabajo.xlsx
├── 📂 Incremento 2
│   ├── Grupo N3 - Incremento 2.docx
│   ├── Presentación - Incremento 2.pptx
│   ├── 📂 Diagrama de secuencia - Vista de proceso
│   ├── Árbol de navegación actualizado.png
│   └── Sprint Incremento 2.xlsx
└── README.md
```

---

## Licencia

Proyecto académico — Universidad Andrés Bello · Ingeniería de Software I & II · 2025–2026
