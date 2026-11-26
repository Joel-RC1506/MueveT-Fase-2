# MueveT

> Documentación oficial del proyecto para el hackatón universitario.

- **Equipo:** Equipo 1
- **Campus:** Toluca
- **Versión / Estado del proyecto:** [PENDIENTE]
- **Repositorio / Demo:** [PENDIENTE]

---

## 1. Resumen ejecutivo

**MueveT** es una aplicación desarrollada por el **Equipo 1** (Campus Toluca) que muestra un mapa de rutas de transporte público —como camiones, combis, microbuses y taxis— para ciudadanos en ciudades sin mapas ni horarios oficiales. Facilita la movilidad urbana al ofrecer precios por ruta, frecuencias, tiempos estimados de llegada y optimización de transbordos. Es innovadora porque combina inteligencia artificial y participación de los usuarios para mapear el transporte concesionado, e incorpora un "termómetro de ocupación" que muestra qué tan llena va cada unidad.

---

## 2. Boceto y concepto

### El problema
En muchas ciudades, el transporte público concesionado (combis, microbuses, camiones y taxis) carece de mapas oficiales de rutas, paradas definidas y horarios confiables. Esta falta de información dificulta la movilidad urbana cotidiana y desincentiva el uso del transporte público frente al automóvil particular.

### Propuesta de solución
**MueveT** centraliza en un mapa accesible la información del transporte público local. Al combinar inteligencia artificial con los aportes de la comunidad de usuarios, la app construye y actualiza las rutas, muestra el costo de cada trayecto, permite conocer qué tan llenas vienen las unidades, indica frecuencias y tiempos de traslado, y optimiza viajes que requieren transbordos.

- **Bocetos / Wireframes de la interfaz:** [PENDIENTE: insertar imágenes o enlace a Figma/prototipo]

### Alineación con los ODS
- **ODS 11 — Ciudades y comunidades sostenibles (Meta 11.2):** El proyecto atiende directamente la Meta 11.2, orientada a garantizar sistemas de transporte seguros, accesibles y sostenibles para todos, al reducir las barreras de información que impiden aprovechar el transporte público frente al automóvil.
- **ODS 10 — Reducción de las desigualdades:** Al incluir un listado de precios por ruta y facilitar el acceso a información sobre el transporte concesionado, la app apoya la planeación económica de los traslados. 

---

## 3. Documentación funcional

A continuación se describen las funciones principales de **MueveT**:

| # | Función | Descripción |
|---|---|---|
| 1 | **Mapeo colaborativo de rutas con IA** | Genera y mantiene actualizado el mapa de rutas de transporte público combinando inteligencia artificial con los aportes de los usuarios de la aplicación. |
| 2 | **Listado de precios por ruta** | Muestra el costo de cada ruta disponible para que el usuario conozca de antemano el impacto económico que tendrá el trayecto en su bolsillo. |
| 3 | **Termómetro de ocupación** | Muestra un indicador visual de qué tan lleno se encuentra el transporte público en la ruta consultada. |
| 4 | **Frecuencia y tiempo estimado de llegada** | Indica cada cuánto pasa el transporte dentro de la ruta del usuario y calcula el tiempo estimado para llegar al destino. |
| 5 | **Optimización de rutas y transbordos** | Calcula la mejor combinación de trayectos y tiempos cuando el usuario necesita cambiar de un transporte a otro para llegar a su destino. |

---

## 4. Documentación técnica

### Link de boceto aplicación
[https://grid-savor-30246568.figma.site/]

### Arquitectura general
[PENDIENTE: describir la arquitectura del sistema (por ejemplo, cliente-servidor, servicios en la nube, flujo de datos entre la app, la base de datos y la IA) y añadir un diagrama si aplica.]

### Stack tecnológico
- **Frontend / Aplicación móvil:** [PENDIENTE: especificar tecnología, p. ej., Flutter, Android nativo]
- **Backend / Servidor:** [PENDIENTE]
- **Base de datos:** [PENDIENTE]
- **Servicios de mapas y geolocalización:** [PENDIENTE]
- **Inteligencia artificial:** Gemini ([PENDIENTE: especificar versión del modelo y SDK/API])

### Integración de Gemini en el flujo de la app
La aplicación contempla el uso de inteligencia artificial junto con los usuarios para el mapeo de rutas de transporte público.
- **Punto de integración en la app:** [PENDIENTE: indicar en qué pantalla o proceso se invoca Gemini]
- **Entradas y salidas:** [PENDIENTE: especificar qué datos recibe Gemini (texto, coordenadas, reportes de usuarios, etc.) y qué resultado devuelve a la app]
- **Propósito específico:** [PENDIENTE: detallar el rol exacto de Gemini dentro del flujo técnico]

### Configuración e instalación para desarrolladores
[PENDIENTE: agregar requisitos previos, comandos de instalación, variables de entorno necesarias (como API keys) e instrucciones para ejecutar el proyecto localmente.]

---

## 5. Manual de usuario

Esta guía está pensada para cualquier persona que use **MueveT** por primera vez.

### Cómo instalar y acceder a la app
1. **Descarga o acceso:** [PENDIENTE: colocar enlace de descarga, archivo APK o instrucciones para abrir la aplicación].
2. **Inicio de sesión / registro:** [PENDIENTE: indicar si se requiere crear una cuenta o si el acceso al mapa es directo].
3. **Permisos necesarios:** [PENDIENTE: indicar si la app solicita permiso de ubicación y cómo activarlo].

### Cómo usar MueveT paso a paso
1. **Explora el mapa de rutas:** Al abrir la aplicación, verás el mapa con las rutas de transporte público disponibles (camiones, combis, microbuses y taxis). [PENDIENTE: describir cómo buscar o elegir origen y destino en pantalla].
2. **Revisa el precio de tu trayecto:** Consulta el listado de precios por ruta para saber cuánto te costará el viaje antes de salir y cuidar tu presupuesto.
3. **Consulta frecuencias y tiempos:** Selecciona la ruta que necesitas para ver cada cuánto pasa el transporte y cuánto tiempo aproximado te tomará llegar a tu destino.
4. **Verifica el termómetro de ocupación:** Antes de subir, observa el indicador del "termómetro de ocupación" para saber qué tan lleno viene el transporte.
5. **Planea viajes con transbordos:** Si no hay un solo transporte que te lleve directo, utiliza la opción de optimización de ruta para ver qué unidades combinar y en cuánto tiempo realizarías el transbordo. [PENDIENTE: indicar el nombre exacto del botón o sección].
6. **Ayuda a mapear rutas:** Si conoces una ruta que falta o ha cambiado, puedes aportar información desde la app para que, junto con la inteligencia artificial, el mapa se mantenga útil para todos. [PENDIENTE: detallar los pasos exactos dentro de la pantalla para enviar un reporte].

### Preguntas frecuentes y soporte
- **¿Qué hago si mi ruta no aparece en el mapa?** [PENDIENTE: indicar cómo reportarla o contribuir al mapeo].
- **Contacto del equipo:** [PENDIENTE: correo o canal de soporte del Equipo 1].

---

## 6. Accesibilidad e impacto

### Inclusión y accesibilidad
- **Acceso equitativo a la información:** MueveT está diseñada para ciudadanos que utilizan combis, microbuses, camiones y taxis en ciudades donde no existen mapas oficiales de rutas, paradas ni horarios, acercando herramientas de movilidad a quienes más dependen del transporte público.
- **Transparencia en el costo del transporte:** Al mostrar un listado de precios por ruta, permite a los usuarios planear sus gastos diarios de movilidad con claridad.
- **Accesibilidad en la interfaz:** [PENDIENTE: detallar características implementadas como soporte para lectores de pantalla, tamaño de fuente adaptable, contraste visual, lenguaje sencillo o funcionamiento con baja conectividad].

### Impacto esperado
- **Mejor experiencia de movilidad urbana:** Reducir la incertidumbre diaria sobre rutas, costos, tiempos de espera, transbordos y nivel de ocupación de las unidades.
- **Impulso al transporte sostenible:** Hacer más práctico y predecible el uso del transporte público para incentivar que más personas lo elijan frente al automóvil particular.
- **Contribución a la Meta 11.2 del ODS 11:** Apoyar el avance hacia sistemas de transporte más seguros, accesibles y sostenibles en entornos urbanos.
- **Indicadores o metas de impacto del proyecto:** [PENDIENTE: añadir métricas proyectadas de usuarios, rutas mapeadas o reducción de tiempos de traslado].
