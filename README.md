# 🛡️ Mi Ruta hacia la Ciberseguridad y Hacking Ético

¡Hola! Soy **Mauro**, programador Junior en transición hacia la ciberseguridad. Este repositorio documenta mi proceso de aprendizaje diario, laboratorios y resúmenes técnicos, aplicando la filosofía de "aprender haciendo" y construyendo un portafolio real para la industria.

---

## 📚 Estructura de Aprendizaje

Mi ruta se divide en etapas estructuradas (siguiendo bases sólidas de redes, sistemas y aplicaciones):
1. **Redes y Fundamentos (Cisco Networking Academy)** 📍 *(En curso)*
2. **Linux y Práctica en Servidores (TryHackMe / OverTheWire)**
3. **Hacking Web (PortSwigger Web Security Academy)**
4. **Cloud & Enterprise Fundamentals (AWS, Azure & Active Directory)**
5. **Certificaciones Oficiales & Proyectos Prácticos**

---

## 📝 Bitácora de Progreso y Apuntes

### Etapa 1: Cisco Networking Academy (Hacking Ético)

#### 📌 Módulos Completados
* ✅ **Introducción al curso**
* ✅ **Módulo 1:** Introducción a la piratería ética y las pruebas de penetración.
* ✅ **Módulo 2:** Planificación y alcance de una evaluación de prueba de penetración.

---

#### 🔄 Módulo Actual
* 🎯 **Módulo 3:** Recopilación de información y análisis de vulnerabilidades.
  * ✅ *Sección 3.2.4:* **Tipos de enumeración**
  * ✅ *Sección 3.2.5:* **Práctica - Exploración de la enumeración a través de la elaboración de paquetes con Scapy**
  * ✅ *Sección 3.2.6:* **Práctica de laboratorio - Enumeración con Nmap**
  * ✅ *Sección 3.2.7:* **Inspección y escucha de paquetes**
  * ✅ *Sección 3.2.8:* **Práctica - Inspección de paquetes y escuchas**
  * ✅ *Sección 3.2.9:* **Práctica de laboratorio - Elaboración de paquetes con Scapy**

##### 🔹 Apuntes clave del Módulo 3 (Enumeración, Scapy y Wireshark):
* **Fecha de estudio:** Octubre de 2026
* **Concepto clave:** Comprensión profunda de la capa de red e inspección de tráfico en tiempo real mediante *packet sniffing* y construcción de paquetes personalizados (*packet crafting*).
* **Puntos clave aprendidos:**
  * **Nmap:** Escaneo activo, tipos de escaneo (`-sS`, `-sV`, `-O`), control de timing (`-T4`) e interpretación de estados de puertos (`open`, `closed`, `filtered`).
  * **Inspección y Escucha (3.2.7 & 3.2.8):** Uso de capturadores de tráfico en interfaces de red específicas. Exportación y análisis de archivos PCAP (`capture1.pcap`) en **Wireshark** para inspeccionar cabeceras Ethernet, IP y TCP/UDP.
  * **Elaboración de paquetes con Scapy (3.2.9):**
    * Uso de la librería interactiva de Python (`sudo scapy`) para forjar capas de red apiladas (`IP() / TCP()`).
    * Captura controlada con `sniff()` asignando interfaces, `count` y `timeout` para evitar bloqueo de sockets.
    * Gestión de permisos e interrupciones del kernel a nivel de consola (`sudo` obligatorio para manipular *raw sockets*).
* **Reflexión desde el desarrollo:** Entender cómo se estructuran manualmente los campos de un paquete de red (como flags SYN, ACK o puertos de destino) permite comprender mejor los análisis de firma en Firewalls/IDS y refuerza la lógica de programación al manipular sockets.

---

## 🚀 Próximos Pasos
* Continuar con las siguientes secciones del Módulo 3 (Análisis de vulnerabilidades y herramientas de evaluación).
* Mantener actualizada la bitácora técnica en GitHub.
