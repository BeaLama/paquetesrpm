Los repositorios en sistemas basados en RPM están configurados en archivos específicos. 
Estos son los lugares más comunes donde se guardan los archivos de configuración de repositorios:

- /etc/yum.repos.d/: Este directorio contiene archivos .repo que definen los repositorios.
  Cada archivo representa un repositorio diferente y contiene información sobre la ubicación del repositorio, sus claves GPG, etc.

- /etc/dnf.repos.d/: Similar a yum.repos.d, este directorio se utiliza en sistemas más recientes que usan dnf como herramienta de gestión de paquetes.
