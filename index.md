# Datenschutzerklärung — BodyLytics

_Stand: Mai 2026 · App-Version: 1.0_

BodyLytics ist eine **Privacy-First**-App für Gewichts- und Körpertracking.
Diese Datenschutzerklärung erklärt klar und vollständig, welche Daten die App
verarbeitet, wo sie gespeichert werden und welche Rechte du hast.

## 1. Verantwortliche Stelle

Tim Remus

Am Brunneck 9,

85521 Ottobrunn

info@liftcode.de

## 2. Welche Daten verarbeitet BodyLytics?

### 2.1 Daten, die du selbst eingibst

Folgende Daten erfasst die App, wenn du sie selbst einträgst:

- **Gewicht** (Pflicht für die App-Funktion)
- **Körperzusammensetzung**: KFA, Umfänge, Hautfaltenmessungen
- **Kalorien** (optional)
- **Profil-Daten**: Geschlecht, Alter, Größe, Aktivitätslevel
- **Zyklus-Daten** (optional, frauen-spezifisch): Periode-Bestätigungen,
  letzter Periodenanfang
- **Profil-Foto** (optional): wird ausschließlich auf deinem Gerät gespeichert
- **Notizen** zu Check-Ins (optional)

### 2.2 Daten von Apple HealthKit (optional, nur mit deiner Einwilligung)

Wenn du die HealthKit-Integration aktivierst, kann BodyLytics:

- Gewichts-, KFA-, BMI- und LBM-Werte **lesen** (Import)
- Berechnete Werte **schreiben** (Export, optional)
- Aktive/Basal-Energie und Ernährungsdaten **lesen** (für TDEE-Berechnung)

Du kannst HealthKit-Zugriff jederzeit in den iOS-Einstellungen widerrufen.

### 2.3 Daten, die NICHT erfasst werden

- ❌ Kein Tracking, keine Analytics
- ❌ Keine Werbe-IDs
- ❌ Kein Standort
- ❌ Keine Kontakte
- ❌ Keine Mikrofon-/Kamera-Aufzeichnung
- ❌ Keine Drittanbieter-SDKs

## 3. Wo werden die Daten gespeichert?

**Ausschließlich lokal auf deinem iPhone** — in einer SwiftData-Datenbank
innerhalb der App-Sandbox. BodyLytics betreibt **keine Server**, sendet **keine
Daten an Drittparteien** und nutzt **keine Cloud-Synchronisation**.

Eine optionale iCloud-Synchronisation ist in zukünftigen Versionen geplant —
wenn du sie aktivierst, werden deine Daten ausschließlich in deinem privaten
iCloud-Account gespeichert (Ende-zu-Ende-verschlüsselt durch Apple).

## 4. Sensible Daten (Cycle-Tracking)

BodyLytics bietet ein **optionales Zyklus-Tracking** für weibliche User. Diese
Daten werden:

- **ausschließlich lokal** auf deinem Gerät gespeichert
- **niemals synchronisiert** (auch nicht via iCloud, falls später aktiviert)
- **niemals an Apple HealthKit weitergegeben** (auch wenn HealthKit aktiv ist)
- **niemals von Werbung oder Drittparteien** ausgewertet

Du kannst Zyklus-Tracking jederzeit in den Einstellungen deaktivieren oder
einzelne Markierungen löschen.

## 5. In-App-Käufe (Premium)

BodyLytics bietet optionale Premium-Features (Coach, erweiterte Analysen,
Apple-Health-Auto-Sync). Käufe laufen **ausschließlich über Apples
StoreKit** — wir erhalten von Apple nur eine Bestätigung, dass der Kauf
gültig ist (keine Zahlungs- oder persönlichen Daten).

## 6. Berechtigungen, die die App anfragt

| Berechtigung | Wofür? | Optional? |
|--------------|--------|:---------:|
| Apple Health (Lesen) | Gewicht / KFA-Import | ja |
| Apple Health (Schreiben) | Trend-Werte zurückschreiben | ja |
| Foto-Mediathek | Profilbild auswählen | ja |
| Mitteilungen | Tägliche Tracking-Erinnerung | ja |

Alle Berechtigungen sind **opt-in** — die App funktioniert auch ohne sie.

## 7. Deine Rechte

Du hast jederzeit das Recht auf:

- **Auskunft** über deine gespeicherten Daten — alle Daten sind in der App selbst
  einsehbar
- **Export** — über Einstellungen → Daten → Exportieren (JSON-Format)
- **Löschung** — einzelne Check-Ins oder die gesamte Datenbank über
  Einstellungen → Daten
- **Berichtigung** — alle Werte sind editierbar

Da BodyLytics **keine Daten sammelt oder weitergibt**, sind klassische
DSGVO-Auskunftsanfragen nicht erforderlich.

## 8. Beta-Phase (TestFlight)

Während der TestFlight-Beta:

- Der Entwickler kann **keine** deiner App-Daten einsehen
- Apple sammelt anonyme **Crash-Reports** und nutzungsstatistiken
  (gemäß Apples Datenschutzrichtlinien) — du kannst das in den iOS-Einstellungen
  → Datenschutz → Analyse-Daten deaktivieren
- Tester-Feedback aus der TestFlight-App wird vom Entwickler gelesen — füge
  keine sensiblen persönlichen Daten in Feedback-Texte ein

## 9. Änderungen dieser Datenschutzerklärung

Bei wesentlichen Änderungen wirst du in der App informiert. Die jeweils
aktuelle Fassung ist immer hier abrufbar.

## 10. Kontakt

Fragen zum Datenschutz? Schreibe an [E-Mail].

---

**Diese App wurde mit Privatsphäre als Kernprinzip entwickelt.** Wenn du
Bedenken hast oder Verbesserungsvorschläge: melde dich gerne.
