# ThermalLabeler

**ThermalLabeler** ist eine Android-Anwendung zum Drucken auf Thermodruckern ohne Bindung an einen bestimmten Hersteller und ohne proprietäre Treiber.

<p align="center">
  <img src="images/roll.jpg" alt="Receipt roll" width="300">
</p>

Wichtig: Die Anwendung ist ausschließlich für Thermodrucker vorgesehen, die die Modi <b>TSPL</b> und/oder <b>ESC/POS</b> unterstützen:
<ul>
  <li><b>TSPL</b> - zum Drucken selbstklebender Etiketten
  <li><b>ESC/POS</b> - zum Drucken auf Thermorollenpapier (Kassenbons, Quittungen, Tickets und andere Dokumente)
</ul>
Die Anwendung ist nicht für herkömmliche Büro-, Tintenstrahl-, Laser- oder andere Drucker geeignet und funktioniert nicht mit ihnen. Unterstützt werden ausschließlich Thermodrucker mit einer kompatiblen <b>TSPL</b>- und/oder <b>ESC/POS</b>-Druckschnittstelle.
<BR>
<BR>Die Anwendung dient als Brücke zwischen Android und einem Thermodrucker und ermöglicht die vollständige Kontrolle über den Druck von Etiketten und Dokumenten auf Thermorollenpapier, wenn Standardlösungen nicht funktionieren oder Einschränkungen verursachen. Sie löst ein praktisches Problem: das Drucken eines Etiketts oder Dokuments von einem Smartphone oder Tablet auf einem kompatiblen Thermodrucker.
<BR>
<BR>Vor dem Drucken wird der Inhalt der Datei automatisch in ein Rasterbild umgewandelt.
<BR>Beim Etikettendruck wird das Rasterbild auf die tatsächliche Etikettengröße skaliert und unter Berücksichtigung von Ausrichtung, Rändern und Druckereinstellungen vorbereitet. Beim Drucken auf einem Bondrucker wird das Rasterbild auf die Papierbreite skaliert.

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
