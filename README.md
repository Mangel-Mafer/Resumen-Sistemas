# Resumen-Sistemas

# ¿Que es un Sistema operativo?

Un sistema operativo es un software que actúa como intermediario entre los usuarios y el hardware de una computadora. 
Su función principal es gestionar los recursos del sistema (como el procesador, la memoria y el almacenamiento) y proporcionar una interfaz para que las personas interactúen con la computadora.

# Historia, generaciones y evolucion de los sistemas operativos

Historia y generaciones:

1- Primera generación (1940-1955):

No había sistemas operativos. Las computadoras eran manejadas manualmente.
Se usaban interruptores y tableros para ingresar programas.

2- Segunda generación (1955-1965):

Sistemas de procesamiento por lotes.
Programas cargados en tarjetas perforadas.
Introducción de sistemas operativos simples para manejar tareas secuenciales.

3- Tercera generación (1965-1980):

Multiprogramación y tiempo compartido.
Los sistemas operativos podían gestionar múltiples usuarios al mismo tiempo.
Ejemplo: UNIX (1971).

4- Cuarta generación (1980-presente):

Interfaces gráficas de usuario (GUI).
Sistemas operativos personales como Windows y macOS.
Aparición de SO móviles (Android, iOS).

5- Quinta generación (futuro):

Enfoque en inteligencia artificial, virtualización y computación en la nube.
Mayor integración con IoT y dispositivos inteligentes.

◦ Niveles de los sistemas operativos
Nivel de usuario: Interacción directa a través de GUI o CLI.
Nivel de servicios: Proporciona herramientas y servicios para ejecutar programas.
Nivel del núcleo (kernel): Gestiona los recursos del hardware y el software.
Nivel del hardware: Interacción directa con los componentes físicos de la computadora.

# 3. ¿Qué hace un administrador de sistemas?

Un administrador de sistemas es responsable de:

+ Configurar y mantener servidores y sistemas operativos.
+ Supervisar el rendimiento del sistema.
+ Implementar medidas de seguridad para proteger datos y redes.
+ Realizar copias de seguridad y restauraciones.
+ Actualizar software y hardware.
+ Resolver problemas técnicos.

# 4. Servicios del sistema operativo

Los sistemas operativos proporcionan servicios como:

1- Gestión de procesos: Crear, planificar y finalizar procesos.

2- Gestión de memoria: Asignar y liberar memoria.

3- Gestión de archivos: Crear, leer, escribir y eliminar archivos.

4- Gestión de dispositivos: Controlar periféricos como impresoras y discos.

5- Seguridad: Autenticación y protección de datos.

6- Interfaz de usuario: GUI o CLI para interactuar con el sistema.

# 5. Dispositivos de entrada, salida y mixtos

Entrada: Capturan datos del usuario o del entorno. Ej.: Teclado, ratón, micrófono, escáner.

Salida: Presentan datos al usuario. Ej.: Monitor, impresora, altavoces.

Mixtos: Funcionan como entrada y salida. Ej.: Pantallas táctiles, unidades USB.

# 6. Manipulación de archivos y directorios

Operaciones comunes:

+ Crear archivos/directorios: touch archivo.txt, mkdir carpeta
+ Leer contenido: cat archivo.txt
+ Copiar archivos: cp origen destino
+ Mover archivos: mv origen destino
+ Eliminar: rm archivo.txt, rmdir carpeta
+ Cambiar permisos: chmod 755 archivo

# 7. Comandos UNIX con ejemplos
1- Navegación:
+ pwd: Muestra el directorio actual.
+ ls: Lista archivos en un directorio.
  
2- Gestión de archivos y directorios:
+ mkdir nueva_carpeta: Crear una carpeta.
+ rm archivo.txt: Eliminar un archivo.
  
3- Permisos:
+ chmod 755 script.sh: Cambiar permisos.
  
4- Procesos:
+ ps: Ver procesos en ejecución.
+ kill 1234: Terminar un proceso.

5- Búsqueda:
+ find /ruta -name "archivo.txt": Buscar un archivo.
  
6- Redirección:
+ ls > lista.txt: Redirigir salida a un archivo.

# 8. VIM: Introducción y comandos básicos

VIM (Vi IMproved) es un editor de texto avanzado que se utiliza en sistemas UNIX/Linux. Es una versión mejorada de vi con características adicionales como resaltado de sintaxis.

Modos en VIM:

1- Modo comando: Navegar y ejecutar comandos (por defecto).
2- Modo inserción: Editar texto (i para entrar, Esc para salir).
3- Modo línea de comandos: Ejecutar comandos (: seguido de un comando).

Comandos básicos:
+ Abrir un archivo: vim archivo.txt
+ Insertar texto: Presiona i para ingresar al modo de inserción.
+ Guardar y salir: :wq
+ Salir sin guardar: :q!
+ Navegar:
  - h: Izquierda, l: Derecha, j: Abajo, k: Arriba.
+ Buscar texto: /palabra

# 9. Administración de la protección y seguridad en un sistema operativo

Un sistema operativo asegura la protección y seguridad de los datos y recursos a través de:

1- Autenticación: Verifica la identidad del usuario (contraseñas, biometría).
2- Autorización: Controla el acceso basado en permisos.
3- Encriptación: Protege los datos almacenados o transmitidos.
4- Control de acceso: Usa listas de control de acceso (ACL) para permisos.
5- Cortafuegos: Previene conexiones no autorizadas.
6- Actualizaciones y parches: Corrige vulnerabilidades.

# 10. Leer el estado del sistema (Administrador de tareas y comandos UNIX equivalentes)

En Windows:
+ Administrador de tareas: Presiona Ctrl + Shift + Esc para monitorear procesos, CPU,
  RAM y red.

En UNIX/Linux (equivalentes):
+ top: Muestra procesos en ejecución y uso de recursos.
+ htop: Versión interactiva de top.
+ free -h: Muestra memoria usada/libre.
+ df -h: Espacio en disco.
+ ps aux: Lista procesos en detalle.


# 11. Sistema de Control de Versiones

Un Sistema de Control de Versiones (VCS) es una herramienta que registra los cambios realizados en archivos a lo largo del tiempo, facilitando la colaboración y el seguimiento de versiones.

Tipos:

+ Centralizado (CVCS): Un repositorio central (ej.: Subversion).
+ Distribuido (DVCS): Cada usuario tiene una copia completa del historial (ej.: Git).

Beneficios:

+ Colaboración eficiente.
+ Seguimiento de cambios.
+ Reversión a versiones anteriores.


# 12. GIT: Comandos básicos explicados con ejemplos
Git es un DVCS popular para gestionar código fuente.

+ Configuración inicial:
- git config --global user.name "Tu Nombre"
- git config --global user.email "tuemail@example.com"

Comandos esenciales:

1) Iniciar repositorio:
+ git init: Crea un repositorio en el directorio actual.

2) Seguimiento de archivos:
+ git add archivo.txt: Agrega un archivo al área de preparación.

3) Guardar cambios:
+ git commit -m "Mensaje del commit": Confirma los cambios.

4) Historial:
+ git log: Muestra el historial de commits.

5) Ramas:
+ git branch: Lista ramas.
+ git checkout -b nueva_rama: Crea y cambia a una nueva rama.

6) Fusionar ramas:
+ git merge rama: Fusiona otra rama en la actual.

7) Repositorio remoto:
+ git clone URL: Clona un repositorio remoto.
+ git push origin main: Sube cambios al servidor remoto.
+ git pull: Obtiene cambios del servidor remoto.

# 13. ¿Qué es un proceso?
Un proceso es una instancia de un programa en ejecución. Incluye el código del programa, su estado y los recursos asignados (CPU, memoria, archivos).

Estados de un proceso:

1- Nuevo: Se está creando.
2- Listo: Espera para ser ejecutado.
3- Ejecución: Se está ejecutando en la CPU.
4- Bloqueado: Espera recursos (E/S).
5- Terminado: Ha finalizado su ejecución.

+Ejemplos:
- Abrir un navegador es un proceso.
- Cada pestaña en un navegador puede ser un subproceso.
