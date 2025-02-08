# 🛠️ Tutorial: Manejo de Paquetes RPM en Rocky Linux

## 0. Presentación  
👋 En este video tutorial, aprenderás cómo manejar los paquetes RPM en la distribución **Rocky Linux**. Veremos cómo buscar, instalar, actualizar, verificar y desinstalar paquetes utilizando el gestor de paquetes **DNF**.

## 1. Introducción: ¿Qué son los paquetes RPM?  
📦 **RPM** (Red Hat Package Manager) es un sistema de gestión de paquetes utilizado en distribuciones como **RHEL**, **CentOS**, y **Rocky Linux**. Permite la instalación, actualización, verificación y eliminación de software de manera eficiente.

## 2. Distribución Rocky Linux  
🐧 **Rocky Linux** es una distribución Linux basada en **RHEL**. Se creó como respuesta al cambio de CentOS Stream, buscando ofrecer una alternativa gratuita y estable para entornos de producción y servidores. Rocky Linux es 100% compatible con RHEL, lo que lo hace una opción ideal para empresas que buscan estabilidad.

### Características de Rocky Linux:  
- ✅ Compatible con **RHEL**.  
- 💡 Enfoque en **estabilidad** y **soporte a largo plazo (LTS)**.  
- ⚙️ Gestiona paquetes con **RPM** y **DNF**.  
- 🌐 100% **Open Source** y desarrollado por la comunidad.

## 3. Repositorios en Rocky Linux  
📁 Los **repositorios** son las fuentes de donde se descargan los paquetes. En Rocky Linux, la configuración de los repositorios se encuentra en los archivos dentro del directorio `/etc/yum.repos.d/`.

## 4. Caso práctico

### a) **Actualizar el sistema**  
🔄 Para mantener tu sistema actualizado, puedes usar el siguiente comando:

```bash
sudo dnf update -y
