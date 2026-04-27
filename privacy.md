# Privacy Policy — Sol y Sombra

**Last updated: 2026-04-23 · v1.0**

This policy describes what data Sol y Sombra (the "App") collects, why, and how we handle it. We've tried to write it in plain language. Three official versions follow: English, Español (Castellano), Català.

---

## English

### TL;DR
- We don't collect, store, or send your personal data anywhere.
- The App asks for your location *only* to centre the map. It never leaves your phone.
- Saved venues, preferred language, and other settings live in your device's local storage. We can't see them.
- The App talks to two third-party services (Open-Meteo for weather, OpenStreetMap for map tiles). Each is described below.
- No tracking, no analytics, no ads, no accounts, no in-app purchases in v1.

### What we collect
**Nothing — on our servers.** Sol y Sombra has no user account, no backend database tied to you, no analytics service that we run.

### What's stored on your device
The App uses your phone's local storage (`localStorage` in the WebView; `Preferences` plugin via Capacitor) to remember:
- Saved venues you've hearted (a list of venue IDs).
- Your preferred language (`en`, `es`, or `ca`).
- Your sun/shade FAB choice (`sun` or `shade`).
- A flag indicating whether you've completed the onboarding.

These are stored only on your device. Uninstalling the App deletes them.

### Location
The App asks the operating system for your location **only** when you tap the locate button (📍). We use your latitude and longitude to centre the map and to compute distances to nearby venues. Your location is **not** transmitted to us, to advertisers, or to anyone else. It exists only in the App's memory and is discarded when the App closes.

You can decline the location prompt. The App still works — it'll just centre on Plaça de Catalunya by default.

### Third-party services
The App makes anonymous network requests to two services:

1. **Open-Meteo** (`api.open-meteo.com`) — weather data for the selected city (Barcelona, Madrid, Castelldefels). We send only the city's coordinates (a fixed value, not yours) and receive temperature/UV/conditions. Open-Meteo's privacy policy: https://open-meteo.com/en/privacy
2. **OpenStreetMap** / **Carto** (`*.tile.openstreetmap.org`, `*.basemaps.cartocdn.com`) — map tiles. Standard HTTP requests for image tiles based on which area of the map you scroll to. The tile servers see your IP address and which tiles you fetch (this is true of all map apps). OSM privacy: https://wiki.osmfoundation.org/wiki/Privacy_Policy

Both are EU-friendly (GDPR-compliant).

### Crash reports / analytics
**None in v1.** The App has no analytics SDK installed. If we add one in a future version, it will be opt-in and this policy will be updated.

### Ads
**None in v1.** If we add ads in a future version, we'll show Apple's standard App Tracking Transparency prompt and update this policy. Ad-supported tier will always be optional and the App will remain free.

### In-app purchases
**None in v1.** Sol y Sombra is fully free with every feature unlocked at launch. If a Pro tier is added in a future version, the purchase flow will go through the standard App Store / Google Play billing system and this policy will be updated.

### Children
The App is rated 4+ and contains no objectionable content. We don't knowingly collect data from anyone, regardless of age.

### Your rights (GDPR / Spanish LOPDGDD)
Since we don't collect personal data, there's nothing for us to delete or export on your behalf. Everything is on your device — uninstalling the App removes it.

### Contact
Email: nis@reflectly.app

### Changes to this policy
If this policy changes materially, we'll bump the version at the top and note what changed in the App Store release notes.

---

## Español (Castellano)

### TL;DR
- No recopilamos, almacenamos ni enviamos tus datos personales a ningún sitio.
- La App pide tu ubicación *únicamente* para centrar el mapa. Nunca sale de tu móvil.
- Los sitios guardados, el idioma preferido y otros ajustes viven en el almacenamiento local de tu dispositivo. No podemos verlos.
- La App se comunica con dos servicios de terceros (Open-Meteo para el tiempo, OpenStreetMap para los mosaicos del mapa). Cada uno se describe abajo.
- Sin seguimiento, sin analíticas, sin anuncios, sin cuentas, sin compras integradas en la v1.

### Qué recopilamos
**Nada — en nuestros servidores.** Sol y Sombra no tiene cuenta de usuario, no tiene base de datos de backend asociada a ti, no tiene servicio de analíticas que ejecutemos.

### Qué se almacena en tu dispositivo
La App usa el almacenamiento local de tu móvil (`localStorage` en el WebView; plugin `Preferences` vía Capacitor) para recordar:
- Los sitios que has marcado como favoritos (una lista de IDs de sitios).
- Tu idioma preferido (`en`, `es` o `ca`).
- Tu elección del FAB sol/sombra (`sun` o `shade`).
- Una marca que indica si has completado la introducción.

Estos datos se almacenan solo en tu dispositivo. Desinstalar la App los elimina.

### Ubicación
La App pide tu ubicación al sistema operativo **solo** cuando pulsas el botón de localización (📍). Usamos tu latitud y longitud para centrar el mapa y calcular distancias a los sitios cercanos. Tu ubicación **no** se transmite a nosotros, a anunciantes ni a nadie más. Existe solo en la memoria de la App y se descarta al cerrarla.

Puedes rechazar el permiso de ubicación. La App funciona igualmente — simplemente se centrará en la Plaza de Cataluña por defecto.

### Servicios de terceros
La App hace peticiones de red anónimas a dos servicios:

1. **Open-Meteo** (`api.open-meteo.com`) — datos del tiempo para la ciudad seleccionada (Barcelona, Madrid, Castelldefels). Enviamos solo las coordenadas de la ciudad (valor fijo, no las tuyas) y recibimos temperatura/UV/condiciones. Política de privacidad: https://open-meteo.com/en/privacy
2. **OpenStreetMap** / **Carto** (`*.tile.openstreetmap.org`, `*.basemaps.cartocdn.com`) — mosaicos del mapa. Peticiones HTTP estándar de imágenes según el área del mapa que navegas. Los servidores de mosaicos ven tu dirección IP y qué mosaicos pides (esto pasa con todas las apps de mapas). Privacidad OSM: https://wiki.osmfoundation.org/wiki/Privacy_Policy

Ambos cumplen con el RGPD europeo.

### Informes de fallos / analíticas
**Ninguno en v1.** La App no tiene SDK de analíticas instalado. Si añadimos uno en una versión futura, será opt-in y actualizaremos esta política.

### Anuncios
**Ninguno en v1.** Si añadimos anuncios en una versión futura, mostraremos el prompt estándar de App Tracking Transparency de Apple y actualizaremos esta política. El nivel con anuncios será siempre opcional y la App seguirá siendo gratuita.

### Compras integradas
**Ninguna en v1.** Sol y Sombra es totalmente gratuita en el lanzamiento, con todas las funciones desbloqueadas. Si se añade un nivel Pro en una versión futura, el flujo de compra pasará por el sistema estándar de App Store / Google Play y se actualizará esta política.

### Menores
La App está calificada para 4+ y no contiene contenido objetable. No recopilamos conscientemente datos de nadie, sin importar la edad.

### Tus derechos (RGPD / LOPDGDD)
Como no recopilamos datos personales, no hay nada que podamos eliminar o exportar por ti. Todo está en tu dispositivo — desinstalar la App lo borra.

### Contacto
Email: nis@reflectly.app

### Cambios en esta política
Si esta política cambia de forma significativa, subiremos la versión arriba e indicaremos qué cambió en las notas de la versión de la App Store.

---

## Català

### TL;DR
- No recollim, emmagatzemem ni enviem les teves dades personals enlloc.
- L'App demana la teva ubicació *només* per centrar el mapa. Mai surt del teu mòbil.
- Els llocs desats, l'idioma preferit i altres ajustos viuen a l'emmagatzematge local del teu dispositiu. No els podem veure.
- L'App parla amb dos serveis de tercers (Open-Meteo per al temps, OpenStreetMap per als mosaics del mapa). Cada un es descriu a sota.
- Sense seguiment, sense analítiques, sense anuncis, sense comptes, sense compres integrades a la v1.

### Què recollim
**Res — als nostres servidors.** Sol y Sombra no té compte d'usuari, no té base de dades de backend associada a tu, no té servei d'analítiques que executem.

### Què s'emmagatzema al teu dispositiu
L'App utilitza l'emmagatzematge local del teu mòbil (`localStorage` al WebView; plugin `Preferences` via Capacitor) per recordar:
- Els llocs que has marcat com a favorits (una llista d'IDs de llocs).
- El teu idioma preferit (`en`, `es` o `ca`).
- La teva tria del FAB sol/ombra (`sun` o `shade`).
- Una marca que indica si has completat la introducció.

Aquestes dades s'emmagatzemen només al teu dispositiu. Desinstal·lar l'App les elimina.

### Ubicació
L'App demana la teva ubicació al sistema operatiu **només** quan toques el botó de localització (📍). Utilitzem la teva latitud i longitud per centrar el mapa i calcular distàncies a llocs propers. La teva ubicació **no** es transmet a nosaltres, ni a anunciants, ni a ningú més. Existeix només a la memòria de l'App i es descarta quan la tanques.

Pots rebutjar el permís d'ubicació. L'App funciona igualment — simplement es centrarà a la Plaça de Catalunya per defecte.

### Serveis de tercers
L'App fa peticions de xarxa anònimes a dos serveis:

1. **Open-Meteo** (`api.open-meteo.com`) — dades del temps per a la ciutat seleccionada (Barcelona, Madrid, Castelldefels). Enviem només les coordenades de la ciutat (valor fix, no les teves) i rebem temperatura/UV/condicions. Política de privacitat: https://open-meteo.com/en/privacy
2. **OpenStreetMap** / **Carto** (`*.tile.openstreetmap.org`, `*.basemaps.cartocdn.com`) — mosaics del mapa. Peticions HTTP estàndard d'imatges segons l'àrea del mapa que navegues. Els servidors de mosaics veuen la teva adreça IP i quins mosaics demanes (això passa amb totes les apps de mapes). Privacitat OSM: https://wiki.osmfoundation.org/wiki/Privacy_Policy

Tots dos compleixen amb el RGPD europeu.

### Informes d'errors / analítiques
**Cap a la v1.** L'App no té cap SDK d'analítiques instal·lat. Si n'afegim un en una versió futura, serà opt-in i actualitzarem aquesta política.

### Anuncis
**Cap a la v1.** Si afegim anuncis en una versió futura, mostrarem el prompt estàndard d'App Tracking Transparency d'Apple i actualitzarem aquesta política. El nivell amb anuncis serà sempre opcional i l'App continuarà sent gratuïta.

### Compres integrades
**Cap a la v1.** Sol y Sombra és totalment gratuïta al llançament, amb totes les funcions desbloquejades. Si s'afegeix un nivell Pro en una versió futura, el flux de compra passarà pel sistema estàndard d'App Store / Google Play i s'actualitzarà aquesta política.

### Menors
L'App està qualificada per a 4+ i no conté contingut objectable. No recollim conscientment dades de ningú, sense importar l'edat.

### Els teus drets (RGPD / LOPDGDD)
Com que no recollim dades personals, no hi ha res que puguem eliminar o exportar per tu. Tot és al teu dispositiu — desinstal·lar l'App ho esborra.

### Contacte
Email: nis@reflectly.app

### Canvis en aquesta política
Si aquesta política canvia de forma significativa, pujarem la versió a dalt i indicarem què va canviar a les notes de la versió de l'App Store.

---

## How to host this

Apple requires a publicly-accessible URL. Cheapest options:

1. **GitHub Pages** (free) — drop the markdown into a repo, enable Pages, point to `https://yourname.github.io/sol-y-sombra-privacy/`. Markdown renders automatically.
2. **Netlify Drop** (free) — drag-and-drop a folder containing `index.html` (export this markdown to HTML first).
3. **Your own domain** — host at e.g. `https://solysombra.app/privacy`.

Apple's App Store Connect → App Information → **Privacy Policy URL** (one URL per locale or one shared URL — sharing is fine since this doc has all 3 languages stacked).

## What I should update before publishing

- [ ] Replace `nis@reflectly.app` with your preferred support email if different.
- [ ] If you host this at a real URL, update the "Last updated" date and put that URL in App Store Connect.
- [ ] When you add ads / IAP / analytics in v1.1+, re-introduce the corresponding sections in all three locales.
