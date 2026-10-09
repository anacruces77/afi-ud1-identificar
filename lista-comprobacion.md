# Lista de comprobación

## 1. Antes de salir y al llegar a la escena
1. Comprobar que llevo todo el material físico y eléctrico en perfecto estado y repasar la normativa policial legal local de registro e incautación (ENFSI 8.3, 9.1).
2. Preguntar si van a intervenir otras áreas forenses (como huellas dactilares o ADN) para acordar el orden de actuación antes de manipular nada (ENFSI 8.3, 9.1).
3. Tomar nota de quiénes están en la escena, qué hacían, qué han observado y cómo han reaccionado (RFC 3227 3.2).
4. Asegurar que los sospechosos y testigos se mantengan alejados de los equipos informáticos (ENFSI 8.2).
5. Inspeccionar la habitación e identificar todos los dispositivos visibles: servidores, portátiles, USBs, tarjetas SD, discos ópticos y discos magnéticos, etc (NIST SP 800-86 3.1.1).
6. Revisar si hay móviles, PDAs, cámaras digitales o grabadoras que puedan contener pruebas relacionadas (NIST SP 800-86 3.1.1).

## 2. Antes de tocar nada
7. Hacer fotos generales y detalladas de la escena, esquematizar un plano e indicar la ubicación y estado exacto de cada dispositivo (ENFSI 8.2).
8. Comprobar si el equipo está encendido. Si lo está, no apagarlo de inmediato para no perder la memoria RAM ni desencadenar borrados automáticos (RFC 3227 2.2, ENFSI 9.1, ENFSI 9.2).
9. Evaluar si hay datos dinámicos en RAM, volúmenes con cifrado activo o riesgos de reinicio remoto antes de cortar la energía (ENFSI 9.1).
10. Decidir si aislar el dispositivo en una caja de protección contra radiofrecuencia (RF) para evitar accesos o borrados remotos, comprobando que no sufra pérdida de datos por descarga de batería (ENFSI 8.3, ENFSI 9.2).
11. Recordar que desconectar o filtrar la red puede activar mecanismos automáticos del atacante que borren la evidencia (RFC 3227 2.2).
12. Aplicar precauciones anti-ESD en dispositivos propensos a dañarse por electricidad estática (ENFSI 8.3).

## 3. Al decidir qué se adquiere y en qué orden
13. Registrar todos los sistemas involucrados y determinar qué datos son relevantes y legalmente admisibles (RFC 3227 3.2).
14. Iniciar la recolección desde lo más volátil a lo menos volátil: Registros/Caché → RAM/Tablas de red → Archivos temporales → Disco Logs remotos → Topología → Archivos de respaldo (RFC 3227 2.1, RFC 3227 3.2).
15. Ejecutar utilidades de extracción desde medios externos protegidos contra escritura, nunca confiando en los programas del propio sistema investigado (RFC 3227 2.2).
16. Anotar la diferencia entre la hora del sistema y la hora UTC, registrando siempre si cada marca temporal es local o UTC (RFC 3227 2, RFC 3227 3.2).
17. Si la fuente principal no es accesible, identificar alternativas como servidores centralizados de logs, copias de seguridad u otras organizaciones/ISPs (NIST SP 800-86 3.1.1).
18. Evaluar si se requiere la intervención de un administrador de sistemas de confianza para extraer datos específicos sin asumir el control directo del sistema (ENFSI 9.2).

## 4. Preservación, embalaje y cadena de custodia
19. Sellado y etiquetado único de cada objeto en el momento con: referencia única, descripción, ubicación exacta de hallazgo, responsable de la recolección, fecha y hora (ENFSI 8.3).
20. Transportar la evidencia protegida contra impactos físicos, vibraciones, campos magnéticos, electricidad estática y cambios drásticos de temperatura o humedad (ENFSI 8.3).
