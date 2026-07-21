# Principios de Ethernet IEEE 802.3 y Conmutación en Redes Cisco

Una publicación web interactiva desarrollada para explorar la estructura de la trama Ethernet, el proceso de entramado y la evolución hacia las redes conmutadas de alta velocidad sin colisiones.



##  Descripción del Proyecto

Este proyecto es una publicación web de autoría propia diseñada con una interfaz web moderna, oscura y responsiva (*Dark Tech Style*), que incluye animaciones CSS personalizadas para simular el tráfico de datos y la actividad de red.

El objetivo principal es explicar de manera clara, fluida y con un lenguaje accesible los fundamentos del nivel de acceso a red en arquitecturas Cisco, basándose en la literatura oficial.



## Temas Desarrollados

### 1. Módulo 6: Principios de Ethernet (IEEE 802.3)
* **Proceso de Entramado (Framing):** Delimitación de inicio y fin de mensaje en la Capa 2 (Enlace de Datos).
* **Campos de la Trama Ethernet:**
  * Preámbulo y Delimitador de Inicio de Trama (SFD).
  * Direcciones MAC físicas (Origen y Destino de 48 bits).
  * Campo de Longitud / Tipo (Length / Type).
  * Carga útil de Datos y Relleno (Data & Padding, límites de 64 a 1518 bytes).
  * Secuencia de Verificación de Trama (FCS / CRC de 4 bytes).

### 2. Módulo 8: Conmutación Ethernet
* **Evolución del Medio Compartido:** Transición de concentradores (Hubs en Half-Duplex) a Switches inteligentes (Full-Duplex).
* **Construcción de la Tabla CAM:** Proceso de aprendizaje (*Learning*) y reenvío (*Forwarding*).
* **Microsegmentación:** Eliminación de colisiones creando dominios individuales por puerto.
* **Dominios de Red:** Diferencias fundamentales entre Dominios de Colisión y Dominios de Difusión (*Broadcast*).

---

## Fuente y Bibliografía

Contenido adaptado a partir del material curricular oficial:
* **Libro / Curso:** *Cisco Networking Academy Program — CCNA 1 y 2 (Versión 3.1)*
* **Módulo 6:** *Principios de Ethernet* (Objetivos 6.1.5, 6.1.6 y 6.1.7 — Págs. 130-134).
* **Módulo 8:** *Conmutación de Ethernet* (Objetivos 8.1 y 8.2 — Págs. 164-174).



**Autor:** Juan Emiliano Corona Peña  
**Asignatura:** Redes de Datos / Conmutación  
**Año:** 2026
