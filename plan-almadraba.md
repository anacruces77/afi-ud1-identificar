# Plan de identificación y preservación

## 1. Fuentes de evidencia

### A. En el puesto de Marta García
- Portátil Dell de empresa: Portátil en funcionamiento con pantalla bloqueada.
  - Memoria RAM del portátil: Información en tiempo real (sesiones activas, procesos, claves en memoria).
  - Disco duro del portátil: Cifrado con BitLocker, contiene archivos locales, caché y registros del sistema.
- Disco externo de 2 TB negro: Conectado al dock USB-C del portátil.
- Teléfono móvil de empresa (iPhone): Dispositivo encendido utilizado para gestiones y WhatsApp con clientes.
- Teléfono móvil personal de Marta: Ubicado en su bolso personal.

### B. En la oficina y red local
- Pendrive de Javier: Dispositivo USB prestado a Marta el jueves 14 y devuelto el día 15.
- Equipo sobremesa compartido (entrada): Equipo utilizado para impresión/escaneo con una sesión abierta de Outlook Web de otra compañera.
- Servidor de ficheros local: Ubicado en el cuarto de informática, almacena los proyectos.
- Sistema NAS de almacenamiento: Servidor de copias de seguridad en el cuarto de informática.
- Cortafuegos, Router local: Guarda registros de conexiones (logs) de red y sesiones VPN.
- Impresora multifunción: Almacena historial de trabajos de impresión y escaneo.

### C. En la nube y terceros
- Entorno de Microsoft 365, OneDrive: Sincronización de documentos de proyectos y portal de gestión de BitLocker.
- Registros de Bahía Sistemas: Logs de la VPN administrada por la consultora externa.
- Grabaciones de videovigilancia: Cámara domo del pasillo administrada por la comunidad de propietarios del edificio.

---

## 2. Prioridad y riesgo de pérdida
1. Memoria RAM y estado activo del portátil Dell: Si se apaga o reinicia el equipo, los procesos activos, conexiones de red y memoria volátil se perderán definitivamente.
2. Logs del cortafuegos local: El registro se sobrescribe continuamente y solo retiene datos aproximados de una semana. Las conexiones del jueves 14 están a punto de borrarse por rotación.
3. Dispositivos móviles (iPhone de empresa): Un borrado remoto o la descarga completa de la batería podrían bloquear o alterar el acceso a los datos.
4. Pendrive de Javier y Disco externo de 2 TB: Dispositivos de almacenamiento expuestos a manipulación física, borrado o desconexión.
5. Equipo sobremesa de la entrada: Contiene una sesión activa de correo que puede caducar por tiempo de espera.
6. Historial de la impresora multifunción: El búfer de trabajos puede perderse si entra un volumen elevado de nuevas impresiones o si el equipo se reinicia.
7. Servidor de ficheros, NAS y OneDrive: Los archivos y las 14 copias de seguridad del NAS están protegidos en almacenamiento no volátil.
8. Grabaciones del edificio y registros de Bahía Sistemas: Dependen de terceros y de sus políticas internas de retención.

---

## 3. Medidas inmediatas de preservación
- Portátil Dell:
  - No apagar ni reiniciar bajo ninguna circunstancia. Mantener conectado a la corriente para evitar el agotamiento de la batería.
  - Desconectar el cable de red o aislarlo de la red Wi-Fi para impedir borrados o accesos remotos.
  - Fotografiar el estado actual de la pantalla y de los cables conectados.
- Dispositivo móvil de empresa (iPhone):
  - Aislar de las redes inalámbricas (activar Modo Avión) o introducirlo en una funda de protección electromagnética. Mantener cargado.
- Pendrive de Javier:
  - Solicitar a Javier la entrega inmediata del pendrive guardado en su cajón.
  - Guardar en bolsa antiestática, etiquetar y mantener bajo custodia sin conectar a ningún equipo.
- Disco externo de 2 TB:
  - Dejar conectado el portátil o desvincularlo tras volcar la memoria RAM, registrando la desconexión física.
- Cortafuegos local:
  - Realizar de inmediato una copia de exportación de los logs actuales de conexiones antes de que se sobrescribe.
- Equipo de la entrada:
  - Fotografiar la pantalla con la sesión abierta de Outlook Web.
- Terceros (Bahía Sistemas y Administración de fincas):
  - Solicitar formalmente a Bahía Sistemas la congelación e inmovilización de los logs de la VPN y de la auditoría de OneDrive. Enviar petición por escrito a la administración de la comunidad para reservar las grabaciones de la cámara del pasillo del día 14 de marzo entre las 17:00 y las 20:00 h.

---

## 4. Límites de actuación y alternativas
- Móvil personal de Marta:
  - No se puede coger ni registrar el teléfono móvil personal de la trabajadora sin su consentimiento expreso o una resolución judicial.
  - La alternativa es dejar constancia formal de lo que dijo ("en el móvil personal no hay nada del trabajo") y focalizar el análisis en los dispositivos corporativos, servidores y logs de red.
- Claves BitLocker y administración del sistema:
  - Evitar el acceso mediante intentos de contraseña no controlados que puedan bloquear el volumen cifrado.
  - La alternativa es solicitar las claves de recuperación guardadas en el portal de Microsoft con el soporte de Bahía Sistemas.
- Manipulación de evidencias en vivo:
  - No utilizar aplicaciones del propio sistema investigado para extraer evidencias..
  - La alternativa es ejecutar herramientas forenses desde medios externos protegidos contra escritura.

---

## 5. Justificación y trazabilidad normativa
- Toma de notas e identificación inicial de personas y entorno:
  - RFC 3227 (Ap. 3.2): Registrar el estado de la escena, presentes y observaciones iniciales.
  - ENFSI (Ap. 8.2): Mantener a sospechosos y testigos alejados de los equipos informáticos.
- Preservación de la pantalla, entorno físico y fotografías:
  - ENFSI (Ap. 8.2): Tomar fotografías generales y detalladas del escenario antes de manipular dispositivos.
- Decisión de no apagar el portátil de primeras:
  - RFC 3227 (Ap. 2.2), ENFSI (Ap. 9.1, 9.2): Evitar el apagado inmediato para preservar la memoria RAM, evitar la pérdida de volúmenes cifrados activos y prevenir la ejecución de scripts automáticos de borrado.
- Aislamiento de la red y prevención de accesos remotos:
  - ENFSI (Ap. 8.2, 9.2): Aislar los dispositivos móviles y equipos frente a señales de radiofrecuencia (RF) o conexiones remotas.
- Orden de prioridad y volatilidad:
  - RFC 3227 (Ap. 2.1, 3.2): Adquisición ordenada comenzando por la memoria volátil y registros antes de pasar a almacenamiento secundario y respaldos.
- Coordinación con terceros y administradores de sistemas:
  - NIST SP 800-86 (Ap. 3.1.1) y ENFSI (Ap. 9.2): Recurrir a fuentes de datos alternativas (servidores centrales, administradores de confianza, ISPs) para obtener registros.
- Etiquetado, embalaje y cadena de custodia:
  - ENFSI (Ap. 8.2): Identificación única, sellado y protección de cada objeto recuperado para garantizar la admisibilidad legal de la prueba.
