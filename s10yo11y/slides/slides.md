---
theme: default
title: Sovereignty Through Observability
titleTemplate: '%s'
info: |
  Dynatrace on STACKIT, managed by CGI
class: text-left
drawings:
  persist: false
transition: fade
mdc: true
---


# Sovereignty Through Observability

Dynatrace on STACKIT, managed by CGI

Thorsten Jakoby

---
layout: section

---

# Intro
asdf


---
layout: image-right
image: https://github.com/jakobyte1024/abstracts/blob/master/bio/pic/TJ2.jpg?raw=true
---

## `whoami`

Einige Worte über mich

- Profilbild rechts
- 3-4 Stationen
- Kontakt / QR-Code

---
layout: two-cols
---

## CGI

Einige Worte über CGI

::right::

### Platzhalter

- CGI Logo
- Kennzahlen
- Einordnung fuer den Kontext

---
layout: two-cols
---

## Agenda

1. Observability basics
2. Warum O11y fuer Souveraenitaet relevant ist
3. Tool-Auswahl und Dynatrace-Entscheidung
4. USP finden
5. Managed Service auf dem Marketplace
6. Betrieb, Automation und technische Huerden
7. Ausblick auf weitere Services

::right::

### Out of scope

- Werbung
- Sales

---
layout: section

---

# Observability 101

---
layout: two-cols
---

## Was ist Observability?

Observability (O11y) ist mehr als "nur" Monitoring.
Es ist eine Fähigkeit die eine reife IT gezielt einsetzt.

Aus vielen Daten und Quellen wird Gesamtsystem oder gar die ganze IT überwacht. Dazu gibt es "Säulen":
* Logs
* Metrics
* Traces
* Topology, Events

Ziel ist es, Systeme zu verstehen - nicht nur Alarmierungen sammeln

Monitoring beantwortet bekannte Fragen - Observability hilft bei unbekannten Fehlerbildern.


::right::

### Visual

Ein Bild das End To End O11y oder Tracing zeigt

---
layout: two-cols
---

## Aktiv und Passiv



- Wert entsteht erst durch Korrelation und Kontext
- Kernfrage fuer den Talk: Wie wird daraus ein souveraener Service?

- Observability beschreibt Erklaerbarkeit und Diagnosefaehigkeit
- Besonders relevant in verteilten Plattformen und Managed Services

::right::

### Visual

- Gegenueberstellung
- Monitoring vs. Observability

---
layout: section

---

# O11y fuer Souveraenitaet

---
layout: two-cols
---

# Paramount

Bild vom Observability is paramount und erzählen was auf dem Talk da erzählt wird

erklären wegen siem

::right::

### Bild

- Screenshot / Foto
- Callout: "Observability is paramount"

---
layout: two-cols
---

# Transparenz, Kontrolle, Nachvollziehbarkeit

- Transparenz ist Voraussetzung fuer Kontrolle und Auditierbarkeit
- Operative Unabhaengigkeit braucht belastbare Telemetrie
- Regulatorik und Trust-Anforderungen verlangen nachvollziehbaren Betrieb

::right::

### Visual

- Dreiklang-Diagramm
- Audit / Control / Telemetry

---
layout: two-cols
---

# Warum wird das zum Souveraenitaets-Thema?

- Ein Managed Service muss nicht nur sicher sein, sondern belegbar beherrschbar
- Datenhoheit ohne Betriebs-Observability bleibt unvollstaendig
- Souveraenitaet betrifft daher Plattform, Prozesse und Telemetrie
- Ohne O11y ist ein Managed Service auf einer souveraenen Plattform nicht glaubwuerdig

::right::

### Beispiel

- Regulatorik-Iconset
- Architektur mit Trust Boundary

---
layout: section

---
# Tool-Auswahl und Dynatrace-Entscheidung

---
layout: two-cols
---

# Tooling-Landschaft

- Open Source, SaaS, Hybrid und Vendor Suites
- Unterschiedliche Staerken bei UX, Datenmodell, Automation und Enterprise-Funktionen
- Auswahl war kein Default, sondern eine bewusste Abwaegung
- Entscheidungskriterien gingen ueber Features deutlich hinaus

::right::

### Visual

- Marktuebersicht
- 2x2 oder Vergleichstabelle

---
layout: two-cols
---

# Warum wir Dynatrace gewaehlt haben

- Reifes Produkt fuer Enterprise-Observability
- Breite Abdeckung fuer Plattform, Anwendungen und Betrieb
- Gute Eignung fuer Managed-Service-Betrieb statt Einzelprojekt-Nutzung
- Differenzierung nicht nur technisch, sondern auch als vermarktbarer Service

::right::

### Visual

- Decision Matrix
- Vendor-Fit fuer Managed Service

---
layout: section
---

# USP wanted

---
layout: two-cols
---

# BYOK als moeglicher USP

- Bring Your Own Key als Souveraenitaets-Baustein
- Relevanz fuer Trust, Compliance und Datenhoheit
- Untersuchung: Was ist technisch und betrieblich realistisch?
- Produktfrage: Wo entsteht echter Mehrwert statt nur Feature-Checkliste?

::right::

### Visual

- Key Lifecycle
- BYOK Boundary Diagramm

---
layout: two-cols
---

# Produktdifferenzierung statt Feature-Liste

- Ein USP muss technisch glaubwuerdig und operativ tragfaehig sein
- Nicht jede Plattform- oder Security-Funktion taugt als Produktmerkmal
- Interessant ist, was fuer Kunden echten Governance- und Vertrauenswert schafft
- BYOK war deshalb nicht nur Technik-Experiment, sondern Produktforschung

::right::

### Visual

- USP Pyramide
- Kundenwert vs. Aufwand

---
layout: two-cols
---

# Traffic

geht nirgends anders hin

::right::

### Visual

- Routing-Skizze
- Marketplace Traffic Flow

---
layout: section
---

# Marketplace

---
layout: two-cols
---

# Vom Tool zum Produkt

- Zielbild: Dynatrace als Managed Service auf dem STACKIT Marketplace
- Nicht nur Installation, sondern Betriebsmodell, Support und Consumption
- Produktisierung verlangt Standardisierung ohne Verlust der Flexibilitaet
- Marketplace-Kontext bringt technische und kommerzielle Randbedingungen mit

::right::

### Visual

- Vom Produkt zum Service
- Marketplace Architektur

---
layout: two-cols
---

# Pricing und Consumption Issues

- Consumption muss fuer Kunden nachvollziehbar und steuerbar sein
- Pricing passt nicht automatisch zu Plattform- und Marketplace-Modellen
- Technische Architektur wird durch Abrechnung und Mandantenfaehigkeit beeinflusst
- Monetarisierung ist kein Nachgedanke, sondern Architekturtreiber

::right::

### Visual

- Pricing-Modell
- Consumption-Funnel

---
layout: section
---

# SRE

---
layout: two-cols
---

# SRE-Ansatz und Automatisierung

- Dynatrace ist kein klassisches SRE-first Produkt aus eigener Entwicklung
- Trotzdem braucht der Service SLO-Denken, Runbooks, Automatisierung und Incident-Lernen
- Terraform fuer Infrastruktur und Standard-Workflows
- Ansible fuer Luecken, Day-2-Operationen und verfahrene Produktstellen

::right::

### Code / Diagramm

- Terraform Pipeline
- Ansible Workflow

~~~yaml
# Beispiel fuer IaC / Automation
pipeline:
  - terraform
  - ansible
~~~

---
layout: two-cols
---

# Quirks, Networking und Support

- ALB-Funktionalitaet gab es nur via API, nicht ueber Terraform
- API Gateway wurde auch fuer monetarisierte APIs und Environment-Routing relevant
- Netzwerktrennung und Environment-Grenzen beeinflussten das Betriebsmodell direkt
- Support war schnell und gut, trotz mehrerer technischer Issues im Aufbau

::right::

### Visual

- Netzwerkdiagramm
- API-Flow

~~~ts
// Beispiel: API statt Terraform
await provisionAlbRule()
~~~

---
layout: section
---

# Ausblick

---
layout: two-cols
---

# Wiederverwendbare Muster

- Dynatrace ist nicht Endpunkt, sondern Blaupause
- Aufbau von Betriebs-, Marketplace- und Automation-Patterns fuer weitere Services
- Wiederverwendbare Bestandteile: Provisioning, Routing, Consumption, Supportmodell

::right::

### Visual

- Reusable Building Blocks
- Service Blueprint

---
layout: two-cols
---

# Welche Services folgen?

- Die Architektur- und Betriebsprinzipien lassen sich auf weitere Produkte uebertragen
- Interessant sind Services mit aehnlichen Anforderungen an Souveraenitaet und Betriebsreife
- Marketplace und Managed Operations werden zur wiederholbaren Plattformfaehigkeit
- Abschlussfrage: Welche weiteren Managed Services profitieren von demselben Ansatz?

::right::

### Visual

- Service-Roadmap
- Portfolio-Optionen

---
layout: two-cols
---

# Kernaussagen

- Observability ist technische und organisatorische Voraussetzung fuer Souveraenitaet
- Die Tool-Auswahl war ein Produkt- und Betriebsentscheid, nicht nur ein Feature-Vergleich
- Marketplace, Consumption und Security beeinflussen die Architektur direkt
- SRE-Prinzipien und starke Automation kompensieren viele Produktgrenzen

::right::

### Summary

- 3 Key Messages
- Optional: QR-Code / Contact

---
layout: end
---

# Danke

Fragen?
