# ThermalLabeler

**ThermalLabeler** ist eine Anwendung zum Drucken von Etiketten auf Thermoetikettendruckern unter Android – herstellerunabhängig und ohne proprietäre Treiber.

**Wichtig:** Die Anwendung ist ausschließlich für Thermoetikettendrucker vorgesehen, die den **TSPL-Modus** unterstützen.
Sie ist **nicht** für herkömmliche Büro-, Tintenstrahl-, Laser-, Beleg- oder andere Druckertypen geeignet und funktioniert mit diesen nicht.
Wenn Ihr Drucker nicht zum Drucken selbstklebender Etiketten vorgesehen ist oder die TSPL-Befehlssprache nicht unterstützt, kann die Anwendung keine Druckaufträge ausführen.

Die Anwendung dient als Brücke zwischen Android und dem Thermoetikettendrucker und bietet vollständige Kontrolle über den Etikettendruck – insbesondere dort, wo Standardlösungen nicht ausreichen oder Einschränkungen verursachen.

Sie löst eine praktische Aufgabe:

**Wie druckt man ein Etikett von einem Android-Smartphone oder -Tablet auf einem gewöhnlichen Thermoetikettendrucker im TSPL-Modus?**

Vor dem Drucken wird der Dateiinhalt automatisch in ein Rasterlayout umgewandelt, an die tatsächliche Etikettengröße skaliert und unter Berücksichtigung von Ausrichtung, Rändern und Druckereinstellungen vorbereitet.

---

## Etikettenvorlagen

Die Anwendung ermöglicht das Erstellen und Speichern mehrerer Etikettenvorlagen mit unterschiedlichen Größen und Druckeinstellungen.

Jede Vorlage enthält folgende Eigenschaften:

* Etikettenbreite und -höhe
* Abstand zwischen den Etiketten (Gap)
* Versatz
* Ausrichtung und Drehung
* Ausrichtungsoptionen
* Vordruckbereich (nicht bedruckbarer Bereich)

Einmal erstellte Vorlagen können beliebig oft wiederverwendet werden und ermöglichen einen schnellen Wechsel zwischen verschiedenen Etikettentypen, ohne die Einstellungen erneut konfigurieren zu müssen.

---

## Direktes Drucken

Der Druck erfolgt direkt über:

* Bluetooth
* USB
* WLAN

Die Anwendung unterstützt das direkte Öffnen von Dateien (PDF, HTML und Bilder) aus Android.

Wird **„Öffnen mit“** oder **„Teilen“** gewählt, wird die Datei automatisch in die Anwendung übernommen und für den Druck vorbereitet.

---

## Integration in Android PrintService

Die Anwendung arbeitet als Android PrintService:

* verfügbar im standardmäßigen Android-Druckdialog
* kann von beliebigen Anwendungen verwendet werden (Warenwirtschaftssysteme, Browser, PDF-Viewer usw.)

---

## Unterstützte Dateiformate

Die Anwendung kann Etiketten aus folgenden Dateitypen öffnen und drucken:

* **PDF** – Dokumente und Layouts aus anderen Anwendungen oder Systemen
* **HTML** – Webseiten und Vorlagen, einschließlich automatisch erzeugter Berichte und Preisschilder
* **Bilder** – PNG, JPG und andere gängige Bildformate

---

## Druckverlauf

Die Anwendung speichert den Verlauf abgeschlossener Druckaufträge.

Für jeden Druckauftrag werden folgende Informationen gespeichert:

* Quelldatei
* Druckeinstellungen

Ein Druckauftrag kann jederzeit erneut geöffnet und ohne erneute Dateiauswahl oder Konfiguration nochmals gedruckt werden.

---

## Vorteile gegenüber herkömmlichen Lösungen

* keine A4-Emulation
* keine Bindung an einen bestimmten Druckerhersteller
* präziser Etikett-zu-Etikett-Druck
* vollständige Kontrolle über den gesamten Druckprozess
* ideal für Lager, Einzelhandel, Logistik und Kennzeichnung

---

## Typische Einsatzbereiche

* Drucken von Preisschildern und Barcodes
* Drucken von Lager- und Versandetiketten
* Drucken aus Warenwirtschaftsprogrammen
* Drucken aus eigenen Android-Anwendungen
