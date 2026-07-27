---
layout: default
title: Datenschutzerklärung
---

# Datenschutzerklärung Medihub Ambient

**Stand:** 27. Juli 2026
**Version:** 1.0
**Anwendbares Recht:** Schweizer Bundesgesetz über den Datenschutz (DSG), ergänzend DSGVO

---

## 1. Verantwortlicher

Verantwortlich für die Datenverarbeitung im Rahmen dieser App:

**Meditext**
Basel, Schweiz
E-Mail: flamur@medihub.ch

---

## 2. Geltungsbereich und Zweck der App

Diese Erklärung gilt für die iOS-App **Medihub Ambient**.

Medihub Ambient ist eine Begleit-App zur Plattform Medihub. Sie nimmt während einer medizinischen Konsultation Ton auf und überträgt diesen an den Medihub-Arbeitsplatz der behandelnden Fachperson, wo daraus die medizinische Dokumentation entsteht.

**Die App richtet sich ausschliesslich an medizinisches Fachpersonal.** Sie ist kein eigenständiges Produkt: die Nutzung setzt einen bestehenden Medihub-Zugang einer Organisation voraus und erfordert eine einmalige Kopplung des Geräts. Ohne diese Kopplung ist die App funktionslos.

Die App ist **kein Medizinprodukt**. Sie stellt keine Diagnosen, gibt keine Behandlungsempfehlungen und trifft keine medizinischen Entscheidungen.

---

## 3. Welche Daten wir verarbeiten

### 3.1 Mikrofon und Audioaufnahmen

Die zentrale Funktion der App ist die Tonaufnahme des Konsultationsgesprächs.

- Die Aufnahme startet **ausschliesslich** auf ausdrückliche Handlung der Fachperson und endet, wenn diese sie beendet oder die Sitzung am Arbeitsplatz abgeschlossen wird.
- Der Ton wird **während** des Gesprächs laufend und verschlüsselt an unsere Server übertragen, nicht lokal auf dem Gerät gesammelt.
- Die Aufnahme läuft technisch bedingt weiter, wenn der Bildschirm gesperrt ist oder eine andere App im Vordergrund steht. Das ist notwendig, damit ein Gespräch nicht durch eine Bildschirmsperre unterbrochen wird, und wird durch die iOS-Berechtigung für Hintergrund-Audio abgebildet.
- Aus dem Ton werden Transkripte und daraus die medizinische Dokumentation erzeugt.
- Die Aufnahme kann **Gesundheitsdaten der Patientin oder des Patienten** enthalten und wird entsprechend als besonders schützenswerte Personendaten im Sinne des DSG behandelt.

Wir verwenden Audioaufnahmen **nicht** zum Training allgemeiner KI-Modelle.

### 3.2 Kamera

Die App verwendet die Kamera **ausschliesslich** zum Scannen des Kopplungs-QR-Codes, der am Medihub-Arbeitsplatz angezeigt wird.

- Das Kamerabild wird **auf dem Gerät** ausgewertet, um den Code zu lesen.
- Es werden **keine** Fotos oder Videos gespeichert und **keine** Bilddaten an uns oder an Dritte übertragen.
- Die Kamera wird zu keinem anderen Zweck aktiviert. Wer den Code nicht scannen möchte, kann die Kopplungsdaten stattdessen manuell einfügen; in diesem Fall wird die Kamera nie verwendet.

### 3.3 Gerätekopplung

Bei der Kopplung erhält und speichert die App **lokal auf dem Gerät** einen Zugangsschlüssel. Dieser enthält eine Geräte-Kennung, eine Nutzer-Kennung und die Kennung der Organisation. Er dient dazu, die Aufnahme dem richtigen Arbeitsplatz zuzuordnen.

Der Schlüssel ist zeitlich begrenzt gültig und kann von der Organisation jederzeit widerrufen werden. Nach einem Widerruf oder Ablauf löscht die App den Schlüssel selbstständig und ist wieder funktionslos, bis sie erneut gekoppelt wird.

### 3.4 Technische Protokolldaten

Zur Sicherstellung des Betriebs verarbeiten wir Verbindungs- und Fehlerprotokolle (Zeitstempel, technische Statusinformationen zur Übertragung).

### 3.5 Was wir nicht erheben

- **Kein** Standortzugriff
- **Keine** Kontakte, Fotos, Kalender oder Gesundheitsdaten aus Apple Health
- **Keine** Werbung, **kein** Werbe-Tracking, **keine** Weitergabe an Werbenetzwerke
- **Keine** Analyse-SDKs von Drittanbietern in der App
- **Keine** Verkaufsdaten oder Zahlungsdaten in dieser App

---

## 4. Einwilligung der Patientin oder des Patienten

**Die Verantwortung für die Einwilligung liegt bei der Fachperson, nicht bei der App.**

Vor jedem Start einer Aufnahme muss die Fachperson die informierte Einwilligung der Patientin oder des Patienten einholen. Die Fachperson bestätigt dies im Medihub-Arbeitsplatz; diese Bestätigung wird zu Prüfzwecken protokolliert.

Ohne vorliegende Einwilligung darf keine Aufnahme gestartet werden.

---

## 5. Wo die Daten liegen

Die Verarbeitung und Speicherung erfolgt **ausschliesslich in Rechenzentren von Microsoft Azure in der Schweiz** (Region Switzerland North). Es findet keine Übermittlung in andere Rechtsräume statt.

Der Zugriff auf Aufnahmen und Dokumentation ist auf die Organisation beschränkt, der das gekoppelte Gerät zugeordnet ist. Andere Organisationen haben keinen Zugriff.

---

## 6. Aufbewahrung und Löschung

Aufnahmen und die daraus erzeugte Dokumentation werden so lange aufbewahrt, wie es für die medizinische Dokumentation und die gesetzlichen Aufbewahrungspflichten der behandelnden Organisation erforderlich ist. Die Organisation legt die Aufbewahrungsdauer im Rahmen der gesetzlichen Vorgaben fest und kann Aufnahmen löschen lassen.

Der lokal auf dem Gerät gespeicherte Zugangsschlüssel wird gelöscht, sobald er widerrufen wird, abläuft oder die App vom Gerät entfernt wird.

---

## 7. Sicherheitsmassnahmen

- Verschlüsselte Übertragung mit TLS 1.2 oder höher
- Verschlüsselung ruhender Daten
- Rollenbasierte Zugriffskontrolle nach dem Prinzip der geringsten Berechtigung
- Zeitlich begrenzte, widerrufbare Zugangsschlüssel pro Gerät
- Audit-Protokollierung der Zugriffe
- Regelmässige Sicherheitsprüfungen und zeitnahe Behebung von Schwachstellen

---

## 8. Auftragsverarbeiter

Wir setzen für den Betrieb der Plattform folgende Dienstleister ein, jeweils auf Grundlage eines Auftragsverarbeitungsvertrags:

- **Microsoft Azure**: Hosting und Speicherung, Region Schweiz
- **Auth0 (Okta)**: Authentifizierung der Nutzerkonten am Medihub-Arbeitsplatz

Eine Weitergabe an weitere Dritte erfolgt nur, wenn dies gesetzlich vorgeschrieben ist oder zum Schutz von Rechten und Sicherheit erforderlich ist.

---

## 9. Ihre Rechte

Sie haben das Recht, Auskunft über die zu Ihrer Person gespeicherten Daten zu verlangen, deren Berichtigung oder Löschung zu fordern, die Verarbeitung einschränken zu lassen, Ihre Daten in einem gängigen Format zu erhalten und eine erteilte Einwilligung jederzeit zu widerrufen.

Betrifft Ihr Anliegen Aufnahmen aus einer Behandlung, wenden Sie sich bitte an die behandelnde Organisation. Diese entscheidet über die Daten ihrer Patientinnen und Patienten. Für alle übrigen Anliegen erreichen Sie uns unter der untenstehenden Adresse.

---

## 10. Kinder

Die App richtet sich ausschliesslich an volljähriges medizinisches Fachpersonal. Wir erheben wissentlich keine Daten von Personen unter 18 Jahren. Eine Nutzung ohne Kopplung durch eine Organisation ist technisch nicht möglich.

---

## 11. Änderungen

Wir können diese Erklärung anpassen. Die überarbeitete Fassung wird mit neuem Stand-Datum auf dieser Seite veröffentlicht.

---

## 12. Kontakt

**Meditext**
Basel, Schweiz
E-Mail: [flamur@medihub.ch](mailto:flamur@medihub.ch)
