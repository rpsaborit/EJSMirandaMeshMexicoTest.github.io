# Primeros Pasos en Meshtastic

---

¡Felicidades! Has decidido unirte a la red Meshtastic. No te preocupes si no sabes nada de electrónica, esta guía es para ti. Aquí te explicamos lo que necesitas y cómo empezar.

## 1. ¿Qué necesitas para empezar?

Para tener tu primer dispositivo Meshtastic funcionando, solo necesitas tres cosas básicas:

* **Un Radio LoRa compatible:** Este es el "cerebro" de tu dispositivo Meshtastic. Los más comunes son los módulos **ESP32 con LoRa integrado** (como los de la serie TTGO T-Beam o Heltec LoRa 32).
    * **¿Dónde comprar?** Puedes encontrarlos en tiendas en línea como Amazon México, Mercado Libre, o directamente en sitios como AliExpress (considera tiempos de envío). Busca "ESP32 LoRa" o "TTGO T-Beam".
* **Una Antena:** La antena es crucial para el alcance de tu dispositivo. Vienen incluidas con la mayoría de los módulos LoRa. Asegúrate de que sea la correcta para la **frecuencia de tu radio** (normalmente 915 MHz en México).
* **Una Batería:** La mayoría de estos dispositivos usan **baterías recargables 18650**. Necesitarás una y un cargador compatible.

### Guía de compra rápida:

* **Recomendación para principiantes:** Busca kits que incluyan el módulo ESP32 LoRa, la antena y, si es posible, un compartimento para batería.
* **Frecuencia:** En México, la frecuencia común para LoRa es **915 MHz**. Asegúrate de que el dispositivo que compres sea para esta frecuencia.
* **Conectores de antena:** Los conectores más comunes son SMA o IPEX. Asegúrate de que la antena sea compatible con el conector de tu radio.

---

## 2. Preparando tu dispositivo

Una vez que tengas tu radio, el siguiente paso es instalar el software de Meshtastic (firmware). Es más sencillo de lo que parece:

* **Conexión:** Conecta tu radio a tu computadora usando un cable USB.
* **Flasheo del Firmware:** Utilizaremos una herramienta sencilla basada en navegador web que hace todo el trabajo por ti. No necesitas instalar programas complejos.
    * **[➡️ Ve al Flasheador Web de Meshtastic](https://flasher.meshtastic.org/)** (Abre en una nueva pestaña)
    * Sigue las instrucciones en pantalla. Generalmente, es seleccionar tu dispositivo, elegir la última versión del firmware y hacer clic en "Flash".

---

## 3. Configuración inicial con la App Móvil

¡Ya casi estás listo! Ahora, usa tu teléfono para configurar tu dispositivo. Usaremos la app de Android como ejemplo, pero los pasos son similares en iOS.

* **Descarga la App:**
    * [**Android: Meshtastic en Google Play Store**](https://play.google.com/store/apps/details?id=com.geeksville.mesh)
    * [**iOS: Meshtastic en Apple App Store**](https://apps.apple.com/us/app/meshtastic/id1555555555) (Busca "Meshtastic" en tu tienda de apps)

* **Conecta tu dispositivo vía Bluetooth:**
    1.  Asegúrate de que tu radio Meshtastic esté encendido y cerca de tu teléfono.
    2.  Abre la app **Meshtastic** en tu teléfono Android.
    3.  La app buscará automáticamente dispositivos Meshtastic cercanos. Cuando veas el tuyo (normalmente aparecerá con un nombre genérico al principio), **selecciónalo**.
    4.  Si te pide permiso para la conexión Bluetooth, **acepta**.

* **Primeros ajustes en la App:**
    Una vez conectado, la app te guiará para configurar tu dispositivo.

    1.  **Nombre del Dispositivo:** Ve a la pestaña **"Settings"** (Ajustes). En la sección **"Radio"**, busca la opción **"User & Module"** y luego **"Node Info"**. Aquí podrás establecer un **"Long Name"** (nombre largo) y un **"Short Name"** (nombre corto). Te recomendamos usar un nombre claro para que otros en la red puedan identificarte, por ejemplo, "UsuarioMX-01" o "MiNodoLoRa".

    2.  **Canales (Channels):**
        En la pestaña **"Channels"** (Canales), verás el canal "Default". Para una mejor experiencia y compatibilidad en la red, te recomendamos usar el canal **"LongFast"** como tu canal principal.

        * **Canal LongFast:** Este es un canal común que ofrece un buen equilibrio entre alcance y velocidad de transmisión.
            * **Contraseña por defecto:** La contraseña por defecto para el canal `LongFast` es `AQ==`. Asegúrate de que la contraseña esté configurada correctamente si te unes a este canal.

    3.  **GPS (si tu dispositivo lo tiene):** Si tu radio tiene GPS (como el TTGO T-Beam), asegúrate de que la ubicación esté activada en la app y que tu radio tenga una señal GPS. Esto permitirá que tu ubicación se comparta automáticamente en la red. Puedes verificar esto en **"Settings" > "Position"**.

    4.  **Guardar y Reiniciar:** Después de hacer cambios, la app te indicará si necesitas **"Write to Device"** (Escribir en el Dispositivo) y **"Reboot"** (Reiniciar) para que los cambios surtan efecto. ¡Hazlo!

---

¡Listo! Tu dispositivo Meshtastic ya está configurado y listo para enviar y recibir mensajes. Ahora, explora los **tutoriales** para aprender a usarlo a fondo y sacarle el máximo provecho.

[**➡️ Ir a la sección de Tutoriales**](tutoriales.md)
