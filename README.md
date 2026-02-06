# 🌱 GitFlow Básico - Guía Práctica

## 📌 Descripción
Este repositorio tiene como finalidad **enseñar de manera sencilla el uso de Git y el flujo de trabajo GitFlow** 🧠💻, mostrando sus fases principales y cómo ayudan a organizar el desarrollo de software en equipo.

Está pensado como un material introductorio para estudiantes y desarrolladores que están comenzando con control de versiones.

---

## 🎯 Objetivo del Repositorio
- Comprender qué es **Git** y para qué sirve 🗂️
- Aprender el flujo básico de trabajo con **GitFlow**
- Identificar las fases principales del proceso
- Promover buenas prácticas en el trabajo colaborativo 🤝

---

## 🧠 ¿Por qué usar Git?
Git es un **sistema de control de versiones** que permite:

- 📜 Llevar historial de cambios
- 🔄 Volver a versiones anteriores
- 👥 Trabajar en equipo sin sobrescribir código
- 🚀 Facilitar la integración y despliegue del software

---

## 🔀 ¿Qué es GitFlow?
GitFlow es una **estrategia de ramificación** que organiza el desarrollo del proyecto usando ramas con propósitos específicos 🌳

Permite:
- Mantener el código estable
- Desarrollar nuevas funcionalidades sin afectar producción
- Corregir errores de forma controlada

---

## 🧩 Fases Simples de GitFlow

### 🟢 1. Rama `main`
- Contiene el código **estable y listo para producción**
- Solo se actualiza cuando el proyecto está validado ✅

### 🔵 2. Rama `develop`
- Rama de desarrollo principal
- Integra las nuevas funcionalidades antes de pasar a producción 🛠️

### 🟡 3. Ramas `feature/*`
- Se crean para desarrollar nuevas funcionalidades ✨
- Ejemplo: `feature/login`, `feature/dashboard`

### 🔴 4. Ramas `hotfix/*`
- Se usan para corregir errores críticos en producción 🐞
- Se integran directamente a `main` y `develop`

---

## 🔄 Flujo de Trabajo Básico
1. Crear una rama `feature` desde `develop`
2. Desarrollar la funcionalidad
3. Unir la rama a `develop`
4. Cuando todo está listo, fusionar `develop` a `main`
5. Corregir errores urgentes usando `hotfix` si es necesario

---

## 🚀 Beneficios de GitFlow
- 📦 Organización clara del proyecto
- 🔐 Mayor estabilidad del código
- 👨‍💻👩‍💻 Mejor trabajo en equipo
- 📈 Escalabilidad del desarrollo

---

## 📚 Público Objetivo
- Estudiantes
- Desarrolladores junior
- Personas que inician con Git y GitHub

---

## 🤝 Contribuciones
Este repositorio es educativo. ¡Si quieres mejorar la explicación o agregar ejemplos, eres bienvenido! 🙌

⭐ ¡No olvides dejar tu estrella si te fue útil
