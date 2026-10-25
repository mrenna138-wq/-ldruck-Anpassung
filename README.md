# FACTORY32 – Öldruckfix

Buildless HTML-Seite: `dist/index.html` enthält Gestaltung, JavaScript und alle Fahrzeugdaten. Keine Installation erforderlich. Die Seite kann direkt als HTML-Datei geöffnet oder auf einem Webserver bereitgestellt werden. Das Original-Logo wird von https://www.factory32.de/img/logo.png geladen; ohne Verbindung erscheint die Textmarke.

## Daten aktualisieren

`vehicles.json` enthält die 68 unveränderten Quelldatensätze. `page.html` ist die Vorlage mit dem Platzhalter `__VEHICLE_DATA__`. Für eine Aktualisierung den Platzhalter mit dem JSON-Inhalt ersetzen und als `dist/index.html` speichern. Alternativ den JSON-Block mit der ID `vehicleData` direkt in der fertigen HTML-Datei bearbeiten. Den sichtbaren Datenstand und die Anzahl der Varianten entsprechend anpassen.

## Redaktioneller Status

Die Excel-Datei bezeichnet die Angaben als Recherchegrundlage und nennt teils technisch widersprüchliche Fremdangaben. Deshalb sind alle Treffer als individuell zu prüfen formuliert. Fehlende Werte wurden nicht ergänzt. Es handelt sich nicht um eine technische Freigabeliste. Vor verbindlichen Kundenzusagen müssen MKB, ECU, Bauzeitraum, Hardware, Softwarestand und Druckregelstrategie geprüft werden.

Anfragen öffnen das E-Mail-Programm mit vorausgefüllten Daten. Es werden keine E-Mails automatisch versendet. Die Filter arbeiten lokal im Browser.
