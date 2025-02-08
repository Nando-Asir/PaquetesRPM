# 🛠️ Tutorial: Manejo de Paquetes RPM en Rocky Linux

## 1. Presentación  
👋 En este video tutorial, aprenderás cómo manejar los paquetes RPM en la distribución **Rocky Linux**. Veremos cómo buscar, instalar, actualizar, verificar y desinstalar paquetes utilizando el gestor de paquetes **DNF**.

## 2. Introducción: ¿Qué son los paquetes RPM?  
📦 **RPM** (Red Hat Package Manager) es un sistema de gestión de paquetes utilizado en distribuciones como **RHEL**, **CentOS**, y **Rocky Linux**. Permite la instalación, actualización, verificación y eliminación de software de manera eficiente.

## 3. Distribución Rocky Linux  
🐧 **Rocky Linux** es una distribución Linux basada en **RHEL**. Se creó como respuesta al cambio de CentOS Stream, buscando ofrecer una alternativa gratuita y estable para entornos de producción y servidores. Rocky Linux es 100% compatible con RHEL, lo que lo hace una opción ideal para empresas que buscan estabilidad.

### Características de Rocky Linux:  
- ✅ Compatible con **RHEL**.  
- 💡 Enfoque en **estabilidad** y **soporte a largo plazo (LTS)**.  
- ⚙️ Gestiona paquetes con **RPM** y **DNF**.  
- 🌐 100% **Open Source** y desarrollado por la comunidad.

## 4. Repositorios en Rocky Linux  
📁 Los **repositorios** son las fuentes de donde se descargan los paquetes. En Rocky Linux, la configuración de los repositorios se encuentra en los archivos dentro del directorio `/etc/yum.repos.d/`.

## 5. [Caso práctico](video/video_tutorial)

### a) **Actualizar el sistema**  
🔄 Para mantener tu sistema actualizado, puedes usar el siguiente comando:\
`sudo dnf update -y`

### b) Buscar paquetes
🔍 Para buscar un paquete, usa el siguiente comando. Por ejemplo, si quieres buscar un paquete:\
`dnf search nombre_paquete`\
Este comando sirve para buscar el paquete que queremos instalar.

### c) Instalar un paquete
📥 Una vez que encuentres el paquete que necesitas, puedes instalarlo con el siguiente comando:\
`sudo dnf install nombre_paquete`\
Este comando instalará el paquete que indiques.

### d) Comprobar que se ha instalado
🔎 Para verificar que un paquete se ha instalado correctamente, usa el siguiente comando:\
`rpm -q nombre_paquete`\
Este comando te mostrará la versión del paquete instalada en tu sistema.

### e) Desinstalar el paquete
❌ Si ya no necesitas un paquete, puedes desinstalarlo con el siguiente comando:\
`sudo dnf remove nombre_paquete`\
Este comando eliminará el paquete de tu sistema.
