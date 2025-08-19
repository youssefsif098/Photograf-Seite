Übersicht
Diese Website ist ein statisches Webprojekt zur Präsentation von Portfolio-Inhalten, optimiert für Mozilla Firefox.

Struktur
HTML5-basierter Aufbau

CSS3 für Layout und Design

Responsives Webdesign (Mobile First Ansatz)

PHP-Formularverarbeitung (nur für Kontaktformular)

Verzeichnisstruktur:

/index.html
/Person.html
/content.html
/shop.html
/kontakt.html
/….
/css/
    philosophie.css
    kontakt.css
    base.css
    Galerie.css
    Content.css
    shop.css
    touren.css
/img/
    (alle Bilddateien)
/form/
    formularverarbeitung.php
/font/
    (alle Fonts)

Optimierung und Besonderheiten
Optimiert für Mozilla Firefox (aktuelle Version)

Responsives Layout für Smartphones, Tablets und Desktops

Navigation:

Mobile Navigation über ein Hamburger-Menü (Checkbox-Steuerung)

Vollständig zugängliche Navigation über Tastatur und Screenreader

Barrierefreiheit:

Alle Bilder mit korrekt gesetztem alt-Attribut

Formularelemente mit Labels und Pflichtfeld-Kennzeichnung (required)

Bilder:

Verwendung von webp und svg-Formaten für bessere Ladezeiten und Qualität

Performance:

Reduzierte Bildgrößen

Minimale externe Abhängigkeiten

Semantisches HTML:

Verwendung von <header>, <nav>, <main>, <section>, <article>, <figure>, <footer> etc.

Browser-Kompatibilität

Browser	Status
Mozilla Firefox	Optimiert
Google Chrome	kompatibel
Microsoft Edge	kompatibel
Safari	nicht vollständig getestet
Hinweise zur Nutzung
PHP wird lediglich für das Absenden des Kontaktformulars benötigt (POST an /form/formularverarbeitung.php).

Keine JavaScript-Abhängigkeiten, vollständige Funktionalität basiert auf HTML/CSS.

Lokales Testen: PHP-Server erforderlich, z.B. mit XAMPP oder MAMP für Formularfunktionalität.

