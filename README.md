La carpeta de roles contiene dos roles para la creacion de carpetas compartidas en Debian y en Rhel8 utilizando el servicio de Samba.

Se pueden crear carpetas compartidas publicas en las que no se pedirán credenciales de acceso y carpetas privadas en las que se pediran estas credenciales.

Las credecianles para la carpeta privada se indicarán mediante variables en la carpeta /roles/privada/vars/main.yml ( usuario y contraseña )


Ambos roles se han probado y testeado con Molecule y cumplen los test de "Lint" y de "Idempotencia"