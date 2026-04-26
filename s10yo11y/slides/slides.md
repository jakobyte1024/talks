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
layout: cover
---


# Sovereignty Through Observability

Dynatrace on STACKIT, managed by CGI

Thorsten Jakoby

---
layout: image-right
image: https://github.com/jakobyte1024/abstracts/blob/master/bio/pic/TJ2.jpg?raw=true
backgroundSize: contain
---

## `whoami`

Thorsten is a technology consultant specializing in cloud security. 

He has designed and built cloud platforms supporting both legacy and modern application stacks across Azure, AWS, GCP, and STACKIT. 

For clients across multiple industries, he has led large-scale migration programs, modernizing on-premises applications to cloud environments with zero downtime. 

Furthermore, Thorsten frequently serves as a trainer for technologies related to containers and Kubernetes. 
He often shares his experience at IT conferences. 


---
layout: image-right
image: /images/cgiOverview.png
backgroundSize: contain
---

## CGI

CGI ist ein globaler IT-Consulting-Konzern mit rund 94.000 Mitarbeitenden weltweit. 
Was CGI besonders macht: globale Stärke und Skalierung, kombiniert mit einem sehr lokalen Delivery-Modell – nah an den Kunden, nah an den Teams und nah an der Umsetzung.

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

Durch Observability entstehen Blickwinkel auf Systeme, durch Korrelation und Kontext.
Diese können verschiedenste Schwerpunkte haben, beispielsweise:

* Erklärbarkeit / Diagnose / Post.Mortem
* Performanz oder Durchlaufzeiten einer Request
* Anamolien beobachten und behandeln
* Resilience Control

Erkennt man daran Gruppen?
::right::

### Beispiele

* Actuator
* Adaptive Scaling (Triggern von Scaling-Entscheidungen)
* SIEM
* Security Enforcement (plötzlich viele Token Requests, ungewöhnlich viele M2M Calls)

---
layout: image-right
image: images/lhca-stage1.png
backgroundSize: contain
---

## Paramount

Dass Observability von besonderer Wichtigkeit sein kann, zeigt sich schnell wenn man typische Angriffsszenarien simuliert.
Wie wird folgendes Szenario erkannt?
* Plötzlich viele Token Requests
* Häufung von Service Calls
* Mehrere fehlgeschlagene Authentifizierungen
* Pods starten offenbar chaotisch neu, jedoch kein Service Down

Ohne Security Context sind dies losgelöste Ereignisse, welche vielleicht gar nicht bemerkt werden.

Im Talk und Lab [Live Hacking Cloud Architectures](https://www.youtube.com/watch?v=ZC1YwpwVlo0) zeigen wir typische Szenarien und enden mit einer Weisheit.


---
layout: section

---

# O11y fuer Souveraenitaet

---
layout: two-cols
---

## Digitale Souveränität

Von der Politik hin zum Techtalk - einer der wichtigsten Begriffe für IT-Expert:innen ist aktuell wohl die Digitale Souveränität. Dazu sagt die EU Commision
> Europe must now strengthen its digital sovereignty and set standards, rather than following those of others – with a clear focus on data, technology and infrastructure.

_Digitale Souveränität bedeutet nicht, Systeme zu besitzen – sondern ihr Verhalten jederzeit nachvollziehen und beeinflussen zu können._

Keine Observability → Keine Kontrolle → Keine Souveränität.

::right::

### Visual
Platzhalter

---
layout: two-cols
---

## Klarer Fall: O11y Plattformen auf EU Cloud 

Souveräne IT-Landschaften brauchen Observability Plattformen.
Doch im Spannungsfeld der Datenhoheit ist das mit manchen Tools schwierig.

Passend zu den wachsenden Befürdnissen nach digitaler Souveränität der Branchen in der EU braucht es in der EU gehostete Observability Plattformen.
Das möchten wir professionell als Managed Service Offering adressieren. 

::right::

### Visual

Platzhalter

---
layout: image-right
image: /images/o11y-platforms.png
backgroundSize: contain
---

## Tooling-Landschaft

Es gibt viele gute Observability Tools - vor allem im Open Source Bereich.
Im Managed Service Offering konzentrieren wir uns zunächst auf
* kommerzielle Anbieter mit entsprechenden Wartungsverträgen
* möglichen Selfhosted Varianten
* wenig Marktbegleiter im öffentlichen Hosting
* eigene Lieferfähigkeit in der Technologieberatung
* Breite Abdeckung fuer Plattform, Anwendungen und Betrieb

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

## Quirks, Networking und Support

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
layout: two-cols
---

## Team shoutout

- CGI Team
- STACKIT Support

::right::

### Visual

- Bilder usw


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
