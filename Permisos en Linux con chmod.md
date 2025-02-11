# Permisos en Linux con `chmod`

| **Permiso** | **Comando chmod** | **Descripción** |
|------------|------------------|-----------------|
| **Sin permisos para nadie** | `chmod 000 archivo.txt` | Nadie puede leer, escribir ni ejecutar. |
| **Solo lectura para todos** | `chmod 444 archivo.txt` | Usuario, grupo y otros solo pueden leer. |
| **Solo escritura para todos** | `chmod 222 archivo.txt` | Usuario, grupo y otros solo pueden escribir. |
| **Solo ejecución para todos** | `chmod 111 archivo.txt` | Usuario, grupo y otros solo pueden ejecutar. |
| **Lectura y escritura para todos** | `chmod 666 archivo.txt` | Usuario, grupo y otros pueden leer y escribir. |
| **Lectura y ejecución para todos** | `chmod 555 archivo.txt` | Usuario, grupo y otros pueden leer y ejecutar. |
| **Escritura y ejecución para todos** | `chmod 333 archivo.txt` | Usuario, grupo y otros pueden escribir y ejecutar. |
| **Todos los permisos para todos** | `chmod 777 archivo.txt` | Usuario, grupo y otros pueden leer, escribir y ejecutar. |
| **Todos los permisos solo al usuario** | `chmod 700 archivo.txt` | Solo el usuario puede leer, escribir y ejecutar. |
| **Solo ejecución para el grupo y otros** | `chmod 711 archivo.txt` | Usuario tiene todos los permisos, grupo y otros solo pueden ejecutar. |
| **Solo escritura para el grupo** | `chmod 020 archivo.txt` | Solo el grupo puede escribir, nadie más tiene acceso. |
| **Todos los permisos al grupo y usuario, ninguno para otros** | `chmod 770 archivo.txt` | Usuario y grupo tienen permisos completos, otros no tienen acceso. |
| **Sin permisos al usuario y todos los permisos al grupo y otros** | `chmod 077 archivo.txt` | Grupo y otros tienen permisos completos, usuario sin acceso. |

