# paquetesrpm

https://www.google.com/url?sa=i&url=https%3A%2F%2Fblogs.iadb.org%2Fconocimiento-abierto%2Fes%2Frepositorios-institucionales%2F&psig=AOvVaw2icBYE-WO6gm8mICMu1gPW&ust=1706476443992000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCJiP96S-_oMDFQAAAAAdAAAAABAI

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


