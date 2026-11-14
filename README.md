# UVa Projects

Trabajos y prácticas del **Grado en Ingeniería Informática** de la **Universidad de Valladolid**, ordenados por curso y cuatrimestre. Cada enlace lleva al repositorio del trabajo, con su propio README: qué hace, cómo está hecho y cómo compilarlo o ejecutarlo.

**Autor:** Javier García González ([@JavivuG](https://github.com/JavivuG)) · Cursos 2021-2022 a 2023-2024

## Proyectos destacados

| Proyecto | Qué es | Stack |
|---|---|---|
| [StudyHub](https://github.com/JavivuG/StudyHub) | Plataforma web colaborativa para compartir apuntes y resolver dudas en foros por asignatura, con roles y votos | Java Servlets/JSP, MySQL, Tomcat, jQuery, Maven |
| [Computación Paralela](https://github.com/JavivuG/Computacion_Paralela) | Alineamiento exacto de secuencias genéticas por fuerza bruta, paralelizado con OpenMP, MPI y CUDA | C, OpenMP, MPI, CUDA |
| [DASR](https://github.com/JavivuG/DASR) | Diseño de una red empresarial de 4 sedes con VLAN, EIGRP, 802.1X/RADIUS, WLAN, NAT y DMZ | Cisco Packet Tracer |
| [ESO](https://github.com/JavivuG/ESO) | Shell de Unix propia (UVash) y versiones de `cat`, `grep`, `zip` y `unzip` con llamadas POSIX | C |

## Por curso

### 1.º curso (2021-2022)

| Cuatr. | Asignatura | Proyecto | Descripción | Stack |
|---|---|---|---|---|
| 1.º | Fundamentos de Programación (FProg) | [Palabras hijas](https://github.com/JavivuG/FProg) | Juego de anagramas: descubrir la palabra base desordenada y sus palabras hijas, con puntuación acumulada en fichero | Java |
| 2.º | Paradigmas de Programación (PdP) | [PAR-King CLI](https://github.com/JavivuG/PAR-King-CLI) | Puzle de aparcamiento tipo Rush Hour en consola, con niveles y récords en ficheros de texto | Python |
| 2.º | Paradigmas de Programación (PdP) | [PAR-King GUI](https://github.com/JavivuG/PAR-King-GUI) | Interfaz gráfica (prototipo sin terminar) de PAR-King: selección de nivel, cuenta atrás y tablero | Python, wxPython |
| 2.º | Fundamentos de Computadores (FCOM) | [2048 en ensamblador](https://github.com/JavivuG/f2048) | Subrutina que aplica un movimiento del 2048 (desplazar y sumar) sobre un tablero 4x4 | MIPS |

### 2.º curso (2022-2023)

| Cuatr. | Asignatura | Proyecto | Descripción | Stack |
|---|---|---|---|---|
| 1.º | Estructuras de Datos y Algoritmos (EDA) | [Vecinos en el plano](https://github.com/JavivuG/EDA) | Simulador de usuarios que notifica entradas y salidas de vecinos: versión con listas y versión optimizada con un Quadtree propio | Python |
| 1.º | Fundamentos de Sistemas Operativos (FSO) | [Minishell y decodificador concurrente](https://github.com/JavivuG/FSO) | Minishell con fork/exec y decodificador de imágenes ASCII con hilos POSIX, buffer circular y semáforos | C, pthreads |
| 1.º | Arquitectura y Organización de Computadores (AOC) | [Prácticas en ensamblador](https://github.com/JavivuG/AOC) | Regula Falsi en coma flotante, itoa/atoi, optimización de MatMul para pipeline y conversión de fechas a epoch | MIPS (MARS) |
| 1.º | Programación Orientada a Objetos (POO) | [Alquiler y reserva de bicis](https://github.com/JavivuG/POO) | Modelo de alquiler de bicis urbanas con polimorfismo de fianzas, distancias por haversine y 48 pruebas JUnit | Java, JUnit 4 |
| 2.º | Estructura de Sistemas Operativos (ESO) | [UVash y utilidades Linux](https://github.com/JavivuG/ESO) | Shell de Unix y versiones propias de cat, grep, zip y unzip con fork, execvp y dup2 | C, Bash |
| 2.º | Interacción Persona-Computadora (IPC) | [Gestor de libros](https://github.com/JavivuG/IPC-entrega1) | Aplicación de escritorio para dar de alta, editar y borrar libros, con validación y atajos de teclado (MVC) | Java Swing |
| 2.º | Interacción Persona-Computadora (IPC) | [Búsqueda de libros](https://github.com/JavivuG/IPC-entrega2) | Biblioteca con tres vistas, búsqueda sin tildes, ordenación e importación/exportación a .txt | Java Swing |
| 2.º | Sistemas Distribuidos (SDist) | [Laboratorios y seminarios](https://github.com/JavivuG/SDist) | Cliente-servidor con sockets TCP/UDP, hilos, colas de mensajes con protocolo propio, RMI y RabbitMQ | Java, RabbitMQ |

### 3.º curso (2023-2024)

| Cuatr. | Asignatura | Proyecto | Descripción | Stack |
|---|---|---|---|---|
| 1.º | Arquitectura de Redes y Servicios (ARS) | [Clientes y servidores con sockets](https://github.com/JavivuG/ARS) | Eco UDP/TCP con servidor concurrente, cliente TFTP y `ping` propio con sockets RAW | C, sockets POSIX |
| 1.º | Diseño, Administración y Seguridad de Redes (DASR) | [Red empresarial](https://github.com/JavivuG/DASR) | Red de 4 sedes (VLAN, EIGRP, 802.1X/RADIUS, WLAN, NAT, DMZ) y prácticas de protocolos Cisco | Cisco Packet Tracer |
| 1.º | Tecnología y Diseño de Bases de Datos (TDBD) | [Base de datos](https://github.com/JavivuG/TDBD) | Del modelo E/R al DDL normalizado (FNBC), con datos de prueba, consultas y triggers | Oracle SQL, PL/SQL |
| 1.º | Garantía y Seguridad de la Información (GSI) | [Prácticas de seguridad](https://github.com/JavivuG/GSI) | Entorno virtual, Nmap, hashing y cifrado, firma digital, pentesting web y SGSI con MAGERIT | VirtualBox, Nmap |
| 2.º | Computación Paralela (CPAR) | [OpenMP, MPI y CUDA](https://github.com/JavivuG/Computacion_Paralela) | Alineamiento exacto de secuencias genéticas paralelizado en memoria compartida, distribuida y GPU | C, OpenMP, MPI, CUDA |
| 2.º | Servicios y Sistemas Web (SSW) | [StudyHub](https://github.com/JavivuG/StudyHub) | Plataforma de aprendizaje colaborativo con foros por asignatura, apuntes, roles y votos | Java Servlets/JSP, MySQL |

## Tecnologías trabajadas

- **Lenguajes:** C, Java, Python, ensamblador MIPS, SQL y PL/SQL, Bash.
- **Sistemas:** procesos, hilos POSIX, semáforos, sockets TCP/UDP/RAW, shells de Unix.
- **Paralelismo y distribución:** OpenMP, MPI, CUDA, RMI, RabbitMQ.
- **Redes y seguridad:** Cisco Packet Tracer, VLAN, EIGRP, 802.1X/RADIUS, NAT, Nmap, criptografía, MAGERIT.
- **Web y escritorio:** Servlets/JSP, Tomcat, MySQL, jQuery, Java Swing, wxPython.
- **Datos:** modelado E/R, normalización, Oracle.

## Nota

Varios trabajos se hicieron en grupo. El README de cada repositorio indica la autoría que consta en el código y en el historial de git.
