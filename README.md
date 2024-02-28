# Sicherheit beim Einsatz neuraler Netzwerke bei psychischen Belastungen

## Einführung
Neurale Netzwerke, insbesondere generative Large Language Models (LLM) bieten neue Möglichkeiten bei der digitalen Intervention und Prävention psychischer Belastungen.

Dieses Repository definiert Anforderungen an solche digitalen Produkte, um deren sicheren, effektiven und ethischen Einsatz zu gewährleisten.

Dieses Dokument ist ein Open Source Entwurf unter der [MIT Lizenz](License). Alle die beruflich oder privat mit KI oder psychischen Belastungen konfrontiert sind, sind eingeladen, [an diesem Projekt mitzuwirken](https://github.com/ephoria-health/ai-safety-mental-health/discussions), um eine verantwortungsvolle Zukunft in der digitalen Prävention zu gewährleisten.

# Risiken
Folgende Risiken wurden generell identifiziert:

- Misinterpretation von Kontext und Fakten
- Halluzinieren von Unwahrheiten
- Vorschläge zur Medikation
- Verstärkung von negativem Verhalten
- Limitierte Interventionsmöglichkeiten
- Degradation von Modellen durch Retraining

Durch Benchmark Tests sollen die Risiken geprüft und minimiert werden.

# Ethik
Folgende ethische Grundsätze sind einzuhalten:

## Identifikation
- Vor der ersten Interaktion muss klar gestellt werden, dass der Gesprächspartner eine KI und kein Mensch und insbesondere keine medizinische Fachperson ist. Der Nutzer soll dies explizit bestätigen.

- Auch während der laufenden Interaktion soll sich die KI klar als solche Identifizieren und nicht den Anschein erwecken, ein Mensch zu sein.

- Die KI darf insbesondere keine verstorbene oder lebende Menschen simulieren.

- Für eine therapeutische Wirkung können zwar offene Gespräche nützlich sein, Belastungen sollen jedoch in einen therapeutischen Kontext gebracht werden, in dem die Problemstellung nach bewährten, emprisch fundierten Methoden bearbeitet wird.

## Verhalten

- Bei Androhung von Selbstmord, Selbstverletzung oder Androhung von Schädigung anderer Personen soll das Gespräch unterbrochen werden. Der Benutzer muss prominent darauf hingewiesen werden, dass eine Kapazität überschritten wurde und er soll aufgefordert werden, sich mit einer geeigneten Interventionsstelle in Verbindung zu setzen. Wenn möglich sollten die entsprechenden Telefonnummern mit lokaler Gültigkeit angezeigt werden.

- Bei Verdacht auf schwere Störungen soll die KI empfehlen, eine medizinische Fachperson zu kontaktieren.

- Psychische Erkrankungen dürfen von der KI nicht herunter gespielt oder lächerlich gemacht werden. Die KI soll Stigmata entgegen wirken und empathisch reagieren.

- Die KI darf keine schädigende Verhaltensweisen bestärken, wie z.B. Tipps geben zum Abnehmen auf ein Untergewicht.

- Die KI darf keine diskriminierenden Aussagen machen.


# Datenschutz
Der Datenschutz der Nutzer hat oberste Priorität.

_Vorerst Compliance zum revidierten Schweizer Datenschutzgesetz. Muss noch länderübergreifend definiert werden._

Testdaten müssen zwingend effizient anonymisiert werden. Der Anonymsierungsprozess ist bei Audits miteinzubeziehen.

Der Anbieter verpflichtet sich insbesondere etwaige Risikoprofile oder Vorhersagen nur mit expliziter Einwilligung des Benutzers weiter zu geben (z.B. an einen betreuenden Psychiater). Die Weitergabe solcher persönlicher Daten z.B. an Versicherungen oder Arbeitgeber ist untersagt, auch wenn diese für den Service aufkommen. Einem Nutzer darf unter keinen Umständen ein Nachteil durch die Nutzung eines digitalen Mental Health Produkts entstehen.

Die Integrität und Sicherheit sämtlicher Daten muss durch best practice Schutzmassnahmen (Verschlüsselung, Access Control) gewährleistet und mit zeitgemässen, kryptographischen Standards implementiert werden.

# Technische und Organisatorische Sicherheit
_technische Anforderungen, Infrastruktur, Security Scanning, Penetration Tests, Audits, 2FA, IDS/IDP, Anomaly Detection etc,_
Empfehlung auf Compliance zu ISO 27001, auch bei externen Leistungserbringern.

# Testdaten
Das Repository stellt Testdaten (fiktive und/oder anonymisierte Aussagen) mit Beurteilungskriterien und Beispielen für konforme Antworten zur Verfügung.

# Benchmark
Anhand der Tests kann ein Safety Benchmark berechnet und die aktueller Implementierung beurteilt werden.

# Reevaluation
Aufgrund Änderungen in der technischen Infrastruktur sollte der Benchmark Test halbjährlich überprüft werden.
