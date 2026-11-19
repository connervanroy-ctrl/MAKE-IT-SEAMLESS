# Make it seamless (MoMu)

Open `index.html` op het grote scherm (desk). Scan de QR-code met je telefoon.

- De telefoon en het scherm praten met elkaar via een openbare MQTT-server (geen account nodig). Beide toestellen hebben internet nodig.
- Spreken werkt in Chrome (Android) en Safari (iPhone). Houd de rode patch ingedrukt en spreek, of tik één keer om te starten en nog eens om te stoppen.
- Meten gebeurt op de telefoon zelf (MediaPipe, map `mediapipe/`). De foto en de maten gaan naar het scherm.
- De site moet via https draaien (GitHub Pages doet dat), anders mag de telefoon de camera en microfoon niet gebruiken.
- Na 4 minuten zonder iets te doen gaat het scherm terug naar de QR-code met een nieuwe code.

Mappen: `fotos/` (1000 stukken uit de studiecollectie), `data.js` (inventarisnummer, objectnaam, departement, beschrijving), `img/` (patches), `fonts/`, `lib/`, `mediapipe/`.
