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

* ✅ **Introducción al curso**

* ✅ **Módulo 1:** Introducción a la piratería ética y las pruebas de penetración.

* ✅ **Módulo 2:** Planificación y alcance de una evaluación de prueba de penetración.

* ✅ **Módulo 3:** Recopilación de información y análisis de vulnerabilidades.

* ✅ **Módulo 4:** Ataques de ingeniería social.

* 🔄 **Módulo 5:** Explotación de redes cableadas e inalámbricas *(En curso)*

#### 🎯 Módulo 5: Explotación de redes cableadas e inalámbricas

* 🔄 *Sección 5.1:* **Explotación de vulnerabilidades basadas en la red**

  * ✅ 5.1.1 Descripción General

  * ✅ 5.1.2 Resolución de nombres de Windows y ataques de SMB

  * ✅ 5.1.3 Práctica - Resolución de nombres de Windows y ataques de SMB

  * ✅ 5.1.4 Práctica de laboratorio - Análisis en busca de vulnerabilidades de pymes con enum4linux

  * ✅ 5.1.5 Envenenamiento de la caché de DNS

  * ✅ 5.1.6 Práctica - Envenenamiento de la caché de DNS

  * ✅ 5.1.7 Explotaciones de SNMP

  * ✅ 5.1.8 Explotaciones de SMTP

  * ✅ 5.1.9 Práctica - Comandos SMTP

##### 🔹 Apuntes clave del Módulo 5:

* **Resolución de Nombres en Windows:** Abuso de protocolos de difusión local como LLMNR (*Link-Local Multicast Name Resolution*) y NBT-NS (*NetBIOS Name Service*) mediante envenenamiento de respuestas para interceptar hashes NTLMv2 en la red interna.

* **Ataques a SMB (Server Message Block):** Enumeración de recursos compartidos sin autenticación (*Null Sessions*), explotación de configuraciones inseguras y captura/retransmisión de credenciales (*SMB Relay*).

* **Enumeración con `enum4linux`:** Herramienta en Kali Linux utilizada para extraer información crítica de sistemas Windows y Samba (usuarios, grupos, políticas de contraseñas, recursos compartidos y OS) a través de protocolos SMB y RPC.

* **Envenenamiento de Caché DNS (DNS Cache Poisoning):** Inserción de registros DNS falsificados en la caché de un servidor recursivo para redirigir el tráfico legítimo hacia servidores maliciosos sin que el usuario lo note.

* **Explotaciones de SNMP (*Simple Network Management Protocol*):** Abuso de cadenas de comunidad por defecto (`public` / `private`) en versiones antiguas (SNMPv1/v2c) para extraer información de red, tablas de enrutamiento o modificar configuraciones de dispositivos.

* **Explotaciones de SMTP (*Simple Mail Transfer Protocol*):** Abuso de servidores mal configurados (*Open Relays*) para envío de correo no autorizado/suplantado, y enumeración de usuarios válidos mediante comandos nativos como `VRFY`, `EXPN` y `RCPT TO`.

#### 📂 Módulos Anteriores Completados

* 🎯 **Módulo 4:** Ataques de ingeniería social

  * ✅ *Sección 4.0:* **Introducción**

    * ✅ 4.0.1 ¿Por qué debería tomar este módulo?

    * ✅ 4.0.2 ¿Qué Aprenderé en este Módulo?

  * ✅ *Sección 4.1:* **Pretextos para un acercamiento y suplantación de identidad**

    * ✅ 4.1.1 Descripción General

    * ✅ 4.1.2 Práctica - Pretextos y suplantación

  * ✅ *Sección 4.2:* **Ataques de ingeniería social**

    * ✅ 4.2.1 Descripción General

    * ✅ 4.2.2 Suplantación de identidad de correo electrónico (Phishing)

    * ✅ 4.2.3 Suplantación de identidad de llamadas telefónicas (Vishing)

    * ✅ 4.2.4 Suplantación de identidad del servicio de mensajes cortos (Smishing)

    * ✅ 4.2.5 Abandono de USB (Baiting / Drop USB)

    * ✅ 4.2.6 Ataques al bebedero (Watering Hole)

    * ✅ 4.2.7 Práctica - Ataque de pivote

    * ✅ 4.2.8 Práctica - Ataques de ingeniería social

  * ✅ *Sección 4.3:* **Ataques físicos**

    * ✅ 4.3.1 Descripción General

    * ✅ 4.3.2 Intrusión por seguimiento (Tailgating / Piggybacking)

    * ✅ 4.3.3 Búsqueda en la basura (Dumpster Diving)

    * ✅ 4.3.4 Vigilancia por encima del hombro (Shoulder Surfing)

    * ✅ 4.3.5 Clonación de credenciales (Badge Cloning / RFID Skimming)

    * ✅ 4.3.6 Práctica - Ataques físicos

  * ✅ *Sección 4.4:* **Herramientas de ingeniería social**

    * ✅ 4.4.1 Descripción general

    * ✅ 4.4.2 Kit de herramientas para ingenieros sociales (SET - Social-Engineer Toolkit)

    * ✅ 4.4.3 Marco de explotación del navegador (BeEF - Browser Exploitation Framework)

    * ✅ 4.4.4 Práctica - Marco de explotación del navegador

    * ✅ 4.4.5 Herramientas de suplantación de identidad de llamadas (Caller ID Spoofing Tools)

    * ✅ 4.4.6 Práctica - Herramientas de suplantación de identidad de llamadas

    * ✅ 4.4.7 Práctica de laboratorio - Exploración del kit de herramientas del ingeniero social (SET)

    * ✅ 4.4.8 Práctica de laboratorio - Uso del marco de explotación del navegador (BeEF)

  * ✅ *Sección 4.5:* **Métodos de influencia**

    * ✅ 4.5.1 Descripción general

    * ✅ 4.5.2 Práctica - Métodos de influencia

  * ✅ *Sección 4.6:* **Resumen**

    * ✅ 4.6.1 ¿Qué aprendí en este módulo?

    * ✅ 4.6.2 Preguntas de reflexión

    * ✅ 4.6.3 Cuestionario - Ataques de ingeniería social

  * ##### 🔹 Apuntes clave del Módulo 4:

    * **Ingeniería Social:** Explotación del factor humano mediante manipulación psicológica, pretexto (Phishing, Vishing, Smishing, Baiting) y pivoteo en la red.

    * **Métodos de Influencia:** Aplicación de principios psicológicos (autoridad, urgencia, escasez, prueba social, simpatía y reciprocidad) para persuadir a la víctima y evadir controles de seguridad.

    * **Seguridad Física y Vector Presencial:**

      * **Tailgating / Piggybacking:** Acceso no autorizado siguiendo de cerca a personal legítimo en áreas restringidas.

      * **Dumpster Diving:** Recuperación de información sensible en desechos no triturados.

      * **Shoulder Surfing:** Observación directa de credenciales o pines.

      * **Clonación de Credenciales:** Abuso de frecuencias RFID/NFC para duplicar tarjetas de acceso.

    * **Herramientas Específicas de Ingeniería Social:**

      * **SET (Social-Engineer Toolkit):** Framework de código abierto orientado al desarrollo de ataques automatizados de ingeniería social (clonación de sitios web para Phishing, generación de payloads maliciosos, vectores de infección por USB/Email).

      * **BeEF (Browser Exploitation Framework):** Herramienta de pruebas de penetración enfocada en explotar vulnerabilidades del lado del cliente enganchando (*hooking*) navegadores web objetivo para ejecutar comandos, phishing en tiempo real y exploración de red interna.

      * **Caller ID Spoofing:** Técnicas y software para falsificar el número de origen en llamadas de voz (Vishing), manipulando la confianza del objetivo.

* 🎯 **Módulo 3:** Recopilación de información y análisis de vulnerabilidades.

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

* ➡️ **Continuar Módulo 5:** Explotación de redes cableadas e inalámbricas (Finalizar Sección 5.1 y avanzar a Sección 5.2).

* Subir laboratorios prácticos realizados en Kali Linux al repositorio.
