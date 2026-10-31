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
  * ✅ *Sección 3.2.10:* **Práctica de laboratorio - Rastreo de redes con Wireshark**
  * ✅ *Sección 3.3.1:* **Descripción General (Análisis de vulnerabilidades)**
  * ✅ *Sección 3.3.2:* **Cómo funciona un típico escáner de vulnerabilidades automatizado**
  * ✅ *Sección 3.3.3:* **Práctica - Cómo funciona un escáner de vulnerabilidades automatizado típico**
  * ✅ *Sección 3.3.4:* **Tipos de análisis de vulnerabilidades**
  * ✅ *Sección 3.3.5:* **Práctica - Tipos de análisis de vulnerabilidades**
  * ✅ *Sección 3.3.6:* **Práctica de laboratorio - Análisis de vulnerabilidades con Kali Tools**
  * ✅ *Sección 3.3.7:* **Desafíos a tener en cuenta al ejecutar un análisis de vulnerabilidades**

##### 🔹 Apuntes clave del Módulo 3 (Análisis de Vulnerabilidades y Herramientas de Kali):
* **Fecha de estudio:** Octubre de 2026
* **Concepto clave:** Ejecución práctica de análisis de vulnerabilidades mediante herramientas especializadas en Kali Linux, priorización de hallazgos y gestión de los límites y desafíos técnicos de los escaneos automatizados.
* **Puntos clave aprendidos:**
  * **Práctica de Tipos de Escaneo (3.3.5):** Diferenciación práctica entre evaluaciones internas/autenticadas (que revelan parches faltantes o malas configuraciones locales) y externas/sin credenciales (que muestran la superficie de ataque expuesta a internet).
  * **Análisis de Vulnerabilidades con Kali Tools (3.3.6):**
    * Uso práctico de scripts NSE (`Nmap Scripting Engine`) enfocado en detección de vulnerabilidades (`--script vuln`).
    * Análisis de configuraciones web y servicios expuestos utilizando herramientas de evaluación de Kali (como OpenVAS/GVM o Nikto para servidores web).
    * Interpretación de salidas, correlación de banners y verificación de falsos positivos.
  * **Desafíos en el Escaneo de Vulnerabilidades (3.3.7):**
    * **Impacto en el rendimiento:** Consumo de ancho de banda y carga de CPU/Memoria en los sistemas auditados durante sondeos intensivos.
    * **Falsos Positivos vs. Falsos Negativos:** La necesidad imperiosa de validar manualmente los hallazgos antes de generar reportes finales.
    * **Limitaciones del escaneo automatizado:** Un escáner identifica firmas conocidas (CVEs), pero no reemplaza el análisis humano ante fallas de lógica de negocio o cadenas de explotación complejas.
* **Reflexión desde el desarrollo:** Como desarrollador, entiendo que las herramientas automatizadas son una excelente primera línea de defensa para auditar software, pero la validación manual y el entendimiento del contexto de la aplicación son esenciales para evitar ruido en los reportes y solucionar brechas reales de seguridad.

---

## 🚀 Próximos Pasos
* Finalizar los desafíos/evaluación restantes del Módulo 3 o avanzar al Módulo 4.
* Continuar documentando prácticas de laboratorio y scripts en GitHub.
