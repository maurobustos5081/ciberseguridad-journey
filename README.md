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

##### 🔹 Apuntes clave del Módulo 3 (Enumeración y Nmap):
* **Fecha de estudio:** Octubre de 2026
* **Concepto clave:** Nmap (*Network Mapper*) es la herramienta estándar de la industria para el descubrimiento de hosts y el análisis de puertos y servicios. Permite pasar de la teoría de la enumeración a la ejecución real de escaneos sobre objetivos.
* **Puntos clave aprendidos:**
  * Uso de diferentes tipos de escaneo (como TCP SYN Scan `-sS`, escaneo de versiones `-sV` y detección de sistemas operativos `-O`).
  * Interpretación de los estados de los puertos: `open` (abierto), `closed` (cerrado), `filtered` (filtrado por un firewall/ACL).
  * Cómo optimizar los tiempos de escaneo y controlar el nivel de ruido en la red mediante flags de velocidad y timing (`-T4`, etc.).
* **Reflexión desde el desarrollo:** Entender cómo Nmap interactúa con los sockets y las capas de red refuerza lo que vimos anteriormente con Scapy. Como programador, analizar el comportamiento de los puertos y servicios ayuda a diseñar aplicaciones más seguras y conscientes de su exposición en la red.

---

## 🚀 Próximos Pasos
* Avanzar con las siguientes secciones del Módulo 3 (Análisis de vulnerabilidades).
* Continuar documentando cada práctica para consolidar el portafolio.
