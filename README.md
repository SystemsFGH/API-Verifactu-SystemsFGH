# API VeriFactu para Delphi y ERPs

Implementación completa del sistema VeriFactu (AEAT) que permite:

- generación de registros verificables  
- firma electrónica (XAdES)  
- envío automático a la Agencia Tributaria  

Diseñado para integrarse en aplicaciones existentes sin modificar su arquitectura.

---

## 🧠 ¿Qué resuelve?

Implementar VeriFactu desde cero implica:

- firma electrónica compleja  
- encadenamiento de hashes  
- comunicación SOAP con AEAT  

Este middleware encapsula todo el proceso en una API local sencilla.

---

<div align="center">

<img src="https://img.shields.io/badge/Estado-v1.0.2_(Windows_&_Linux)-orange?style=for-the-badge&logo=rocket" />
<img src="https://img.shields.io/badge/API-REST_|_JSON-success?style=for-the-badge&logo=json" />
<img src="https://img.shields.io/badge/Modo-On--Premise-blue?style=for-the-badge&logo=server" />

<br><br>

### 🚀 Middleware VeriFactu (B2B)

**Integración directa entre ERP y Agencia Tributaria**

</div>

---

## 📌 ¿Qué es este proyecto?

Este middleware actúa como un **motor local autónomo (On-Premise)**:

👉 Tu ERP envía un JSON  
👉 El sistema procesa:

- firma  
- hash  
- envío a AEAT  

👉 Y devuelve:

- estado  
- CSV  
- URL de verificación  

Sin necesidad de implementar la lógica fiscal completa en tu aplicación.

---

## 🎬 Ejecución real del sistema

<div align="center">

<a href="https://youtu.be/f9E0sY9eQQ8">
<img src="https://img.youtube.com/vi/f9E0sY9eQQ8/maxresdefault.jpg" width="600"/>
</a>

</div>

---

## ⚡ Ventajas del enfoque local

- 🔐 **Privacidad total:** los datos no salen del entorno del cliente  
- 🔑 **Control del certificado:** firma desde el propio sistema  
- 🔄 **Alta disponibilidad:** cola local y procesamiento asíncrono  
- 💾 **Base de datos integrada:** Firebird 5.x  

---

## 💻 Compatibilidad

Compatible con cualquier entorno que pueda enviar HTTP:

- Delphi / C++Builder  
- PHP / Laravel  
- Python / FastAPI  
- .NET / Java  
- Node.js / Go / otros  

---

## 📥 Instalación rápida

### 🪟 Windows

[![Descargar Instalador Windows](https://img.shields.io/badge/Descargar-Windows_v1.0.2-blue?style=for-the-badge&logo=windows)](https://github.com/SystemsFGH/API-Verifactu-SystemsFGH/releases/download/v1.0.2/systemFGH_Setup.exe)

---

### 🐧 Linux

[![Descargar Instalador Linux](https://img.shields.io/badge/Descargar-Linux_v1.0.2-orange?style=for-the-badge&logo=linux)](https://github.com/SystemsFGH/API-Verifactu-SystemsFGH/releases/download/Linux_v1.0%2C2/install.sh)

```bash
wget https://github.com/SystemsFGH/API-Verifactu-SystemsFGH/releases/download/Linux_v1.0%2C2/install.sh
chmod +x install.sh
sudo ./install.sh
