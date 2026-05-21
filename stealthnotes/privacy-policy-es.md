---
layout: default
title: Política de Privacidad y Derechos de Autor
---

[Português](./privacy-policy-pt.html) | [English](./privacy-policy-en.html) | [Español](./privacy-policy-es.html)


# Política de Privacidad y Términos de Derechos de Autor - Stealth Notes

**Última actualización:** 21 de Mayo de 2026

**Sitio web:** [https://andrec84j.github.io/](https://andrec84j.github.io/)

**Stealth Notes** ("nosotros", "nuestro" o "aplicación") es una aplicación de notas ultrasecretas, capturas de pantalla seguras, grabación de video, gestión de documentos y contraseñas, desarrollada con un enfoque absoluto en la privacidad y almacenamiento local-first. Esta Política de Privacidad y Términos de Derechos de Autor describe cómo manejamos sus datos y los términos bajo los cuales se otorga la licencia del software.

---

## PARTE 1 - POLÍTICA DE PRIVACIDAD

### 1. Recopilación y Almacenamiento de Datos

#### 1.1 Arquitectura Local-First (Cofre Cifrado)
Stealth Notes es una aplicación **100% Local-First**. Esto significa que:
*   Todas sus notas de texto, notas flotantes (Post-its), capturas de pantalla, grabaciones de video, documentos importados y contraseñas se guardan y almacenan **exclusivamente en su propio dispositivo**.
*   Para garantizar la máxima seguridad, toda su información confidencial se guarda dentro de un archivo de cofre local seguro y cifrado (`vault.enc`).
*   **No enviamos** sus archivos, contenidos multimedia, textos o contraseñas a nuestros servidores. No disponemos de servidores en la nube para almacenar su contenido personal.
*   **Ausencia de Telemetría:** La aplicación no recopila, rastrea ni envía telemetría, datos analíticos o registros de uso a los desarrolladores. Todo se procesa localmente en su propio equipo.

#### 1.2 Funciones de IA (Inteligencia Artificial) y OCR
Para ofrecer características avanzadas como el reconocimiento de texto y asistencia de edición por IA:
*   **OCR Local (Reconocimiento Óptico de Caracteres):** Este proceso se ejecuta completamente de forma local en su dispositivo utilizando las API nativas de Windows. Sus capturas de pantalla no se envían a internet para el procesamiento OCR.
*   **Servicios de IA Opcionales:** La aplicación permite la integración con API de Inteligencia Artificial (OpenAI, Google Gemini, Anthropic Claude) para ayudarle a redactar, resumir o traducir sus anotaciones.
*   **Claves API del Usuario:** El uso de IA es completamente opcional y requiere que introduzca sus propias claves API (tokens). Estas claves se almacenan localmente en su ordenador de forma segura y encriptada.
*   **Transmisión de Datos de IA:** Al activar una función de IA, solo los datos o textos estrictamente necesarios para esa solicitud específica se envían directamente desde su ordenador al proveedor de IA que haya elegido. Ningún dato pasa por intermediarios o servidores del desarrollador de Stealth Notes. El uso de dichas claves y datos se rige por las políticas de privacidad de sus respectivos proveedores.

---

### 2. Permisos del Dispositivo

Stealth Notes requiere los siguientes permisos del sistema para funcionar correctamente:
*   **Captura y Grabación de Pantalla:** Requerido para tomar capturas de pantalla del escritorio y realizar grabaciones de video cuando usted lo solicite.
*   **Grabación de Audio / Micrófono (Opcional):** Requerido únicamente si desea incluir el audio de su micrófono en sus grabaciones de video locales.
*   **Ejecutar al Inicio (Startup):** Permite que la aplicación se inicie opcionalmente de forma automática al arrancar Windows. Esta opción se puede activar o desactivar fácilmente en cualquier momento a través del menú del icono de la bandeja del sistema (System Tray) o en la configuración de la aplicación.
*   **Acceso al Sistema de Archivos:** Utilizado para leer y escribir sus archivos multimedia exportados, configuraciones de la aplicación y su archivo de cofre cifrado.

---

### 3. Modo Stealth (Protección contra Captura de Ventanas)
La aplicación implementa el **Modo Stealth**, que utiliza API de bajo nivel de Windows para ocultar las ventanas de Stealth Notes y las notas flotantes Post-its de capturas de pantalla o grabaciones de pantalla externas ejecutadas por otros programas. Esto evita que terceros capturen o espíen accidentalmente sus notas confidenciales mientras comparte o graba su pantalla.

---

### 4. Compartir Datos con Terceros
Dado que la aplicación opera completamente de manera local, **no vendemos, alquilamos, compartimos ni divulgamos** ninguna de sus informaciones personales. Usted mantiene el control absoluto y exclusivo sobre sus claves de seguridad y archivos generados.

---

## PARTE 2 - DERECHOS DE AUTOR Y LICENCIA

### 5. Propiedad Intelectual y Derechos de Autor
Todo el código fuente, elementos visuales, gráficos, iconos, marcas y diseños de interfaz de **Stealth Notes** son propiedad exclusiva del desarrollador.
*   **Copyright © 2026 André CJ. Todos los derechos reservados.**
*   Queda estrictamente prohibido descompilar, realizar ingeniería inversa, redistribuir, modificar o sublicenciar este software sin el consentimiento previo por escrito del titular de los derechos de autor.

---

### 6. Modelo de Licencia Freemium y Compras Integradas

Stealth Notes se distribuye bajo un modelo **Freemium** a través de la Microsoft Store:
*   **Versión Gratuita (Límites de Creación):** La versión básica es gratuita y da acceso a todas las herramientas, pero restringe la cantidad de elementos activos que puede mantener creados:
    *   Capturas de Pantalla: límite de **5** elementos
    *   Documentos: límite de **3** elementos
    *   Grabaciones de Video: límite de **3** elementos
    *   Notas Comunes: límite de **5** elementos
    *   Notas Flotantes (Post-its): límite de **3** elementos
    *   Contraseñas: límite de **5** elementos
*   **Desbloqueo Premium:** Los usuarios pueden eliminar permanentemente todos los límites de creación realizando una compra única dentro de la aplicación (Upgrade Premium), procesada de forma totalmente segura directamente a través de la Microsoft Store.

---

### 7. Exclusión de Responsabilidades (Disclaimer)
Este software se proporciona "tal cual" (as is), sin garantías de ningún tipo, expresas o implícitas.
*   **Responsabilidad de la Contraseña Maestra:** Como no disponemos de servidores de recuperación en la nube, **guardar y recordar su Contraseña Maestra y su Clave de Recuperación del cofre cifrado es de total y exclusiva responsabilidad del usuario**. Si olvida su contraseña maestra o pierde su clave de recuperación, será técnicamente imposible recuperar los datos contenidos en el cofre.
*   El desarrollador no se hace responsable de las pérdidas de datos causadas por fallos de hardware, eliminaciones accidentales de archivos o pérdida de claves de acceso.

---

### 8. Soporte y Contacto
Para reportar errores, solicitar asistencia o realizar preguntas, visite el sitio oficial del desarrollador en [https://andrec84j.github.io/](https://andrec84j.github.io/) o use los enlaces de soporte provistos en la Microsoft Store.
