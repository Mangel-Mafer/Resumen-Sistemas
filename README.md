# Resumen-Sistemas

# ¿Que es un Sistema operativo?

Un sistema operativo es un software que actúa como intermediario entre los usuarios y el hardware de una computadora. 
Su función principal es gestionar los recursos del sistema (como el procesador, la memoria y el almacenamiento) y proporcionar una interfaz para que las personas interactúen con la computadora.

![image](https://github.com/user-attachments/assets/f6fe4039-9b42-4ea9-ba2a-c4e234212bbf)


# 2- Historia, generaciones y evolucion de los sistemas operativos

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

![image](https://github.com/user-attachments/assets/2b77a818-0771-42de-b41f-7b19cabdc7b5)


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

![image](https://github.com/user-attachments/assets/44b5230e-eec3-4e8c-81b8-2c0e8027768d)


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
- git config --global user.name "Nombre"
- git config --global user.email "email@email.com"

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

+ Ejemplos:
- Abrir un navegador es un proceso.
- Cada pestaña en un navegador puede ser un subproceso.

# 14. Estado de un proceso

Los estados de un proceso describen su ciclo de vida en el sistema operativo. Son los siguientes:

1. Nuevo (New): El proceso está siendo creado.

2. Listo (Ready): El proceso está preparado para ejecutarse, pero espera que la CPU esté libre.

3. Ejecución (Running): La CPU está ejecutando las instrucciones del proceso.

4. Bloqueado (Blocked): El proceso está esperando un recurso o evento, como la finalización de una operación de E/S.

5. Terminado (Terminated): El proceso ha concluido su ejecución.

# 15. Comandos UNIX para la administración de procesos
Listar procesos:
+ ps: Lista los procesos actuales.
+ top: Monitorea los procesos en tiempo real.
+ htop: Versión interactiva de top.

Manejar procesos:
+ kill PID: Termina un proceso específico.
+ killall nombre_proceso: Termina todos los procesos con ese nombre.
+ nice: Inicia un proceso con prioridad específica.
+ renice: Cambia la prioridad de un proceso en ejecución.
+ bg: Envía un proceso al fondo.
+ fg: Trae un proceso al frente.

# 16. Planificación de procesos

La planificación de procesos es una técnica para asignar CPU a los procesos según diferentes algoritmos.

• FCFS (First-Come, First-Served):
- Ordena procesos según su llegada.
- Ventajas: Simple y fácil de implementar.
- Desventajas: Puede causar problemas de ineficiencia como el problema del convoy.

• Round Robin (RR):
- Asigna un tiempo fijo (quantum) a cada proceso.
- Si un proceso no termina dentro del quantum, pasa al final de la cola.
- Ventajas: Tiempo de respuesta predecible.
- Desventajas: Si el quantum es demasiado corto, puede generar sobrecarga.

• SJF (Shortest Job First):
- Prioriza los procesos con menor tiempo de ejecución.
- Ventajas: Minimiza el tiempo promedio de espera.
- Desventajas: Puede generar injusticia hacia procesos largos.

# 17. Comandos adicionales

Wildcards:

+ *: Sustituye cualquier cantidad de caracteres.
Ej.: ls *.txt lista todos los archivos .txt.

+ ?: Sustituye un solo carácter.
Ej.: ls archivo?.txt lista archivo1.txt, archivo2.txt, etc.

+ [ ]: Define un rango de caracteres.
Ej.: ls archivo[1-3].txt lista archivo1.txt, archivo2.txt y archivo3.txt.

- Comandos esenciales:

1) Eliminar archivos:
+ rm archivo.txt: Elimina un archivo.
+ rm -r carpeta: Elimina una carpeta y su contenido.

2) Mover/renombrar archivos:
+ mv archivo.txt destino/: Mueve el archivo.
+ mv viejo.txt nuevo.txt: Renombra un archivo.

3) Listar archivos:
+ ls -l: Muestra detalles de los archivos.
+ ls -lh: Incluye tamaño en un formato legible.

4) Obtener peso ordenado:
+ du -h --max-depth=1 | sort -h: Lista el tamaño de archivos/carpetas ordenado.

# 18. Unidades de almacenamiento

Las unidades de almacenamiento son dispositivos que guardan datos de manera temporal o permanente.

- Tipos principales:
1- Primarias: Memoria RAM, caché (rápida, pero volátil).
2- Secundarias: Discos duros (HDD), unidades de estado sólido (SSD).
3- Terciarias: Cintas magnéticas, usadas para copias de seguridad.
4- Cuaternarias: Almacenamiento en la nube.

Capacidades comunes:
+ Kilobyte (KB): 1,024 bytes.
+ Megabyte (MB): 1,024 KB.
+ Gigabyte (GB): 1,024 MB.
+ Terabyte (TB): 1,024 GB.

# 19. Jerarquía de Memoria

La jerarquía de memoria se basa en el equilibrio entre velocidad, tamaño y costo.

1) Registros (CPU):
Muy rápidos, pero limitados en capacidad.

2) Caché:
Almacena datos de acceso frecuente.

3) RAM:
Acceso rápido, pero volátil.

4) Almacenamiento secundario:
Discos duros y SSD (mayor capacidad, más lento).

5) Almacenamiento terciario:
Cintas y unidades externas (gran capacidad, baja velocidad).

# 20. Localidad Espacial y Temporal

La localidad espacial y temporal es un principio que describe cómo los programas acceden a datos y cómo esto afecta al rendimiento del sistema.

Localidad temporal:
+ Un dato recientemente accedido tiene alta probabilidad de ser accedido nuevamente 
  pronto.
+ Ejemplo: Variables en bucles.

Localidad espacial:
+ Si se accede a un dato, es probable que datos cercanos en memoria también sean 
  accedidos.
+ Ejemplo: Acceso secuencial a elementos de un arreglo.

Estas propiedades optimizan el uso de cachés y mejoran el rendimiento del sistema.

# 21. Tipos de sistemas de archivos

Un sistema de archivos organiza y gestiona cómo se almacenan y acceden los datos en dispositivos de almacenamiento.

Principales tipos:

1) FAT32:
+ Compatible con varios sistemas.
+ Limitación: Archivos de hasta 4 GB.

2) NTFS:
+ Usado en Windows.
+ Soporta grandes volúmenes, permisos avanzados y cifrado.

3) ext4:
+ Predeterminado en Linux.
+ Rendimiento y confiabilidad mejorados.

4) HFS+/APFS:
+ Utilizado por macOS.
+ APFS es más rápido y seguro.

5) exFAT:
+ Compatible con sistemas modernos, ideal para unidades USB.

# 22. Virtualización

La virtualización permite ejecutar múltiples sistemas operativos o aplicaciones en un solo hardware físico al simular recursos como CPU, memoria y almacenamiento.

Tipos:

1- Virtualización de hardware:
+ Ej.: VMware, VirtualBox.

2- Virtualización de servidor:
+ Consolida servidores físicos.

3- Virtualización de red:
+ Divide una red física en múltiples redes virtuales.

Ventajas:
+ Ahorro de costos.
+ Pruebas en entornos aislados.
+ Mayor flexibilidad y escalabilidad.

# 23. Concurrencia

La concurrencia ocurre cuando múltiples tareas o procesos parecen ejecutarse simultáneamente, compartiendo recursos del sistema.

- Mecanismos clave:
+ Hilos (Threads): Múltiples tareas dentro de un proceso.
+ Bloqueos (Locks): Evitan conflictos en recursos compartidos.
+ Semáforos: Controlan el acceso a recursos críticos.

Ejemplo:
- Un servidor web maneja múltiples solicitudes de clientes concurrentemente.

# 24. Persistencia

La persistencia se refiere a la capacidad de un sistema para retener datos más allá de la vida útil de un programa o proceso.

Ejemplos:

+ Bases de datos.
+ Archivos en disco.
+ Configuraciones guardadas.

Relación con almacenamiento:

La persistencia depende del uso de sistemas de almacenamiento no volátiles, como discos duros o SSD.

# 25. Lenguajes de programación a bajo nivel (C)

C es un lenguaje de bajo nivel que combina control de hardware con eficiencia.

Características:

+ Acceso directo a memoria mediante punteros.
+ Control de recursos del sistema.
+ Ideal para desarrollar sistemas operativos y software de bajo nivel.

Ejemplo:

![image](https://github.com/user-attachments/assets/7a68491f-c33a-4c00-afba-72f933e6aff0)


# 26. Sistemas Operativos Móviles: Emulador de Android

Un emulador de Android permite ejecutar aplicaciones de Android en una computadora simulando un dispositivo móvil.

Ejemplos de emuladores:
+ Android Studio Emulator: Herramienta oficial para desarrolladores.
+ BlueStacks: Enfocado en juegos y uso general.

Funciones:
+ Simula hardware móvil (GPS, cámara).
+ Prueba de aplicaciones en diferentes versiones de Android.

# 27. Permisos de archivos en UNIX: Explicación y ejemplos con chmod

En UNIX, cada archivo tiene permisos para lectura (r), escritura (w) y ejecución (x) para tres categorías:

1) Usuario (u): Propietario.
2) Grupo (g): Usuarios del grupo del propietario.
3) Otros (o): Resto de los usuarios.

Representación de permisos:
+ rwxr-xr--: Usuario tiene todos los permisos, grupo puede leer/ejecutar, otros solo 
  leer.
Uso de chmod:
+ Cambiar permisos con valores simbólicos:

   + chmod u+r archivo.txt: Agrega permiso de lectura al usuario.
   + chmod g-w archivo.txt: Quita permiso de escritura al grupo.

+ Cambiar permisos con valores numéricos:

  + chmod 755 archivo.txt:
  + Usuario: rwx (7), Grupo: r-x (5), Otros: r-x (5).
