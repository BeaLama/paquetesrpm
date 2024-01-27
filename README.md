# paquetesrpm
# Introducción

Los paquetes RPM (Red Hat Package Manager) son una forma de distribuir software en sistemas basados en Red Hat, como CentOS y Rocky Linux. En este repositorio, exploraremos los aspectos básicos relacionados con los paquetes RPM.

# Distribución Rocky Linux

Rocky Linux es una distribución de Linux basada en el código fuente de Red Hat Enterprise Linux (RHEL). Algunas características notables incluyen la estabilidad, la seguridad y el soporte a largo plazo.


# Repositorios

En sistemas basados en RPM, la configuración de los repositorios se almacena en archivos en el directorio `/etc/yum.repos.d/`. Cada archivo en este directorio define un repositorio con información como URL, nombre y configuraciones adicionales.


# Caso Práctico

## a) Actualizar el sistema

```bash
sudo yum update


yum search nombre_del_paquete


