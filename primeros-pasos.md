# Primeros Pasos en Meshtastic

---

¡Felicidades! Has decidido unirte a la red Meshtastic. No te preocupes si no sabes nada de electrónica, esta guía es para ti. Aquí te explicamos lo que necesitas y cómo empezar.

## 1. ¿Qué necesitas para empezar?

Para tener tu primer dispositivo Meshtastic funcionando, solo necesitas tres cosas básicas:

* **Un Radio LoRa compatible:** Este es el "cerebro" de tu dispositivo Meshtastic. Los más comunes son los módulos ESP32 con LoRa integrado (como los de la serie TTGO T-Beam o Heltec LoRa 32).
    * **¿Dónde comprar?** Puedes encontrarlos en tiendas en línea como Amazon México, Mercado Libre, o directamente en sitios como AliExpress (considera tiempos de envío). Busca "ESP32 LoRa" o "TTGO T-Beam".
* **Una Antena:** La antena es crucial para el alcance de tu dispositivo. Vienen incluidas con la mayoría de los módulos LoRa. Asegúrate de que sea la correcta para la frecuencia de tu radio (normalmente 915 MHz en México).
* **Una Batería:** La mayoría de estos dispositivos usan baterías recargables 18650. Necesitarás una y un cargador compatible.

### Guía de compra rápida:

* **Recomendación para principiantes:** Busca kits que incluyan el módulo ESP32 LoRa, la antena y, si es posible, un compartimento para batería.
* **Frecuencia:** En México, la frecuencia común para LoRa es **915 MHz**. Asegúrate de que el dispositivo que compres sea para esta frecuencia.
* **Conectores de antena:** Los conectores más comunes son SMA o IPEX. Asegúrate de que la antena sea compatible con el conector de tu radio.

## 2. Preparando tu dispositivo

Una vez que tengas tu radio, el siguiente paso es instalar el software de Meshtastic (firmware). Es más sencillo de lo que parece:

* **Conexión:** Conecta tu radio a tu computadora usando un cable USB.
* **Flasheo del Firmware:** Utilizaremos una herramienta sencilla basada en navegador web que hace todo el trabajo por ti. No necesitas instalar programas complejos.
    * **[➡️ Ve al Flasheador Web de Meshtastic](https://flasher.meshtastic.org/)** (Abre en una nueva pestaña)
    * Sigue las instrucciones en pantalla. Generalmente, es seleccionar tu dispositivo, elegir la última versión del firmware y hacer clic en "Flash".

## 3. Configuración inicial con la App Móvil

¡Ya casi estás listo! Ahora, usa tu teléfono para configurar tu dispositivo:

* **Descarga la App:**
    * [**Android: Meshtastic en Google Play Store**](https://play.google.com/store/apps/details?id=com.geeksville.mesh)
    * [**iOS: Meshtastic en Apple App Store**](https://apps.apple.com/us/app/meshtastic/id1555555555) (Busca "Meshtastic" en tu tienda de apps)
* **Conecta tu dispositivo:** Abre la app y sigue los pasos para conectar tu teléfono a tu radio Meshtastic vía Bluetooth.
* **Primeros ajustes:** La app te guiará para ponerle un nombre a tu dispositivo y unirte a un canal (puedes empezar con el canal predeterminado).

---

¡Listo! Tu dispositivo Meshtastic ya está configurado y listo para enviar y recibir mensajes. Ahora, explora los **tutoriales** para aprender a usarlo a fondo y sacarle el máximo provecho.

[**➡️ Ir a la sección de Tutoriales**](tutoriales.md)
