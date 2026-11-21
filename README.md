# 🛡️ Mi Ruta hacia la Ciberseguridad y Hacking Ético

¡Hola! Soy **Mauro**, programador Junior en transición hacia la ciberseguridad. Este repositorio documenta mi proceso de aprendizaje diario, laboratorios y resúmenes técnicos, aplicando la filosofía de "aprender haciendo" y construyendo un portafolio real para la industria.

## 📚 Estructura de Aprendizaje

Mi ruta se divide en etapas estructuradas (siguiendo bases sólidas de redes, sistemas y aplicaciones):

1. **Redes y Fundamentos (Cisco Networking Academy)** 📍 *(En curso)*

2. **Linux y Práctica en Servidores (TryHackMe / OverTheWire)**

3. **Hacking Web (PortSwigger Web Security Academy)**

4. **Cloud & Enterprise Fundamentals (AWS, Azure & Active Directory)**

5. **Certificaciones Oficiales & Proyectos Prácticos**

## 📝 Bitácora de Progreso y Apuntes

### Etapa 1: Cisco Networking Academy (Hacking Ético)

#### 📌 Módulos Completados

- ✅ **Introducción al curso**

- ✅ **Módulo 1:** Introducción a la piratería ética y las pruebas de penetración.

- ✅ **Módulo 2:** Planificación y alcance de una evaluación de prueba de penetración.

- ✅ **Módulo 3:** Recopilación de información y análisis de vulnerabilidades.

- ✅ **Módulo 4:** Ataques de ingeniería social.

- 🔄 **Módulo 5:** Explotación de redes cableadas e inalámbricas *(En curso)*

#### 🎯 Módulo 5: Explotación de redes cableadas e inalámbricas

- 🔄 *Sección 5.1:* **Explotación de vulnerabilidades basadas en la red** *(En curso)*

  * ✅ 5.1.1 Descripción General

  * ✅ 5.1.2 Resolución de nombres de Windows y ataques de SMB

  * ✅ 5.1.3 Práctica - Resolución de nombres de Windows y ataques de SMB

  * ✅ 5.1.4 Práctica de laboratorio - Análisis en busca de vulnerabilidades de SMB con enum4linux

  * ✅ 5.1.5 Envenenamiento de la caché de DNS

  * ✅ 5.1.6 Práctica - Envenenamiento de la caché de DNS

  * ✅ 5.1.7 Explotaciones de SNMP

  * ✅ 5.1.8 Explotaciones de SMTP

  * ✅ 5.1.9 Práctica - Comandos SMTP

  * ✅ 5.1.10 Explotaciones de FTP

  * ✅ 5.1.11 Ataques de tipo Pass-the-Hash

  * ✅ 5.1.12 Ataques basados en Kerberos y LDAP

  * ✅ 5.1.13 Kerberoasting

  * ✅ 5.1.14 Ataques en ruta

  * ✅ 5.1.15 Práctica - Kerberos, LDAP y ataques en ruta

  * ✅ 5.1.16 Práctica de laboratorio - Ataques en la ruta con Ettercap

##### 🔹 Apuntes clave del Módulo 5 (Sección 5.1):

- **Resolución de Nombres en Windows y SMB:** Explotación de protocolos de red local (LLMNR, NBT-NS) para capturar hashes NTLMv2 y enumeración de recursos compartidos, usuarios y políticas mediante `enum4linux` y SMB.
- **DNS Cache Poisoning:** Inyección de registros falsos en la caché de un servidor DNS para redirigir el tráfico de los usuarios hacia servidores controlados por el atacante.
- **Explotaciones de SNMP:** Abuso de cadenas de comunidad por defecto (`public` / `private`) en versiones SNMPv1/v2c para extraer información crítica de configuración y topología de dispositivos de red.
- **Explotaciones de SMTP:** Enumeración de cuentas de usuario válidas en servidores de correo mediante comandos nativos como `VRFY`, `EXPN` y `RCPT TO`, además de pruebas de *Open Relay*.
- **Explotaciones de FTP:** Intercepción de credenciales y archivos en texto plano (puertos 20/21), abuso de acceso anónimo (`anonymous`) mal configurado y ataques de fuerza bruta.
- **Pass-the-Hash (PtH):** Técnica de movimiento lateral donde el atacante autentica sesiones utilizando directamente el hash NTLM capturado de un usuario sin necesidad de descifrar la contraseña en texto plano.
- **Kerberos, LDAP y Kerberoasting:** Enumeración de Active Directory vía LDAP y extracción de tickets de servicio (TGS) cifrados con claves de cuentas de servicio para crackearlos offline (*Kerberoasting*).
- **Ataques en ruta (MitM) con Ettercap:** Interceptación y manipulación de tráfico en redes locales mediante envenenamiento ARP (*ARP Spoofing*) utilizando Ettercap.

#### 📂 Módulos Anteriores Completados

- 🎯 **Módulo 4:** Ataques de ingeniería social.

  * ✅ *Sección 4.0:* **Introducción** (4.0.1 - 4.0.2)

  * ✅ *Sección 4.1:* **Pretextos para un acercamiento y suplantación de identidad** (4.1.1 - 4.1.2)

  * ✅ *Sección 4.2:* **Ataques de ingeniería social** (Phishing, Vishing, Smishing, Baiting, Watering Hole, Pivote)

  * ✅ *Sección 4.3:* **Ataques físicos** (Tailgating, Dumpster Diving, Shoulder Surfing, Clonación RFID)

  * ✅ *Sección 4.4:* **Herramientas de ingeniería social** (SET, BeEF, Caller ID Spoofing, Labs 4.4.7 y 4.4.8)

  * ✅ *Sección 4.5:* **Métodos de influencia** (Autoridad, Escasez, Urgencia, Prueba social)

  * ✅ *Sección 4.6:* **Resumen** (4.6.1 - 4.6.3)

- 🎯 **Módulo 3:** Recopilación de información y análisis de vulnerabilidades.

  * ✅ *Sección 3.2.4:* Tipos de enumeración

  * ✅ *Sección 3.2.5:* Práctica - Exploración de la enumeración a través de la elaboración de paquetes con Scapy

  * ✅ *Sección 3.2.6:* Práctica de laboratorio - Enumeración con Nmap

  * ✅ *Sección 3.2.7:* Inspección y escucha de paquetes

  * ✅ *Sección 3.2.8:* Práctica - Inspección de paquetes y escuchas

  * ✅ *Sección 3.2.9:* Práctica de laboratorio - Elaboración de paquetes con Scapy

  * ✅ *Sección 3.2.10:* Práctica de laboratorio - Rastreo de redes con Wireshark

  * ✅ *Sección 3.3.1:* Descripción General (Análisis de vulnerabilidades)

  * ✅ *Sección 3.3.2:* Cómo funciona un típico escáner de vulnerabilidades automatizado

  * ✅ *Sección 3.3.3:* Práctica - Cómo funciona un escáner de vulnerabilidades automatizado típico

  * ✅ *Sección 3.3.4:* Tipos de análisis de vulnerabilidades

  * ✅ *Sección 3.3.5:* Práctica - Tipos de análisis de vulnerabilidades

  * ✅ *Sección 3.3.6:* Práctica de laboratorio - Análisis de vulnerabilidades con Kali Tools

  * ✅ *Sección 3.3.7:* Desafíos a tener en cuenta al ejecutar un análisis de vulnerabilidades

  * ✅ *Sección 3.4.1:* Descripción general (Análisis de resultados)

  * ✅ *Sección 3.4.2:* Fuentes para una mayor investigación de vulnerabilidades

  * ✅ *Sección 3.4.3:* Práctica de laboratorio - Investigación de fuentes de información de vulnerabilidades

  * ✅ *Sección 3.4.4:* Cómo lidiar con una vulnerabilidad

  * ✅ *Sección 3.5.1:* ¿Qué aprendí en este módulo?

  * ✅ *Sección 3.5.2:* Preguntas de reflexión

  * ✅ *Sección 3.5.3:* Cuestionario - Recopilación de información y análisis de vulnerabilidades

## 🚀 Próximos Pasos

- ➡️ **Continuar Módulo 5:** Avanzar con las siguientes secciones de explotación en redes cableadas e inalámbricas.

- Subir laboratorios prácticos realizados en Kali Linux al repositorio.