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

# `whoami`

Einige Worte über mich

---

# CGI

Einige Worte über CGI

---

# Agenda

0. whoami
1. Observability basics
2. Warum O11y fuer Souveraenitaet relevant ist
3. Tool-Auswahl und Dynatrace-Entscheidung
4. USP finden
5. Managed Service auf dem Marketplace
6. Betrieb, Automation und technische Huerden
7. Ausblick auf weitere Services

---
layout: section

---

# Observability basics

---

# Was ist Observability?

- Mehr als Monitoring: Logs, Metrics, Traces, Topology, Events
- Ziel: Systeme verstehen, nicht nur Alarmierungen sammeln
- Observability beschreibt Erklaerbarkeit und Diagnosefaehigkeit
- Besonders relevant in verteilten Plattformen und Managed Services

---

# Warum ist das mehr als Monitoring?

- Monitoring beantwortet bekannte Fragen
- Observability hilft bei unbekannten Fehlerbildern
- Wert entsteht erst durch Korrelation und Kontext
- Kernfrage fuer den Talk: Wie wird daraus ein souveraener Service?

---
layout: section

---

# O11y fuer Souveraenitaet

---

# Paramount

Bild vom Observability is paramount und erzählen was auf dem Talk da erzählt wird

---

# Transparenz, Kontrolle, Nachvollziehbarkeit

- Transparenz ist Voraussetzung fuer Kontrolle und Auditierbarkeit
- Operative Unabhaengigkeit braucht belastbare Telemetrie
- Regulatorik und Trust-Anforderungen verlangen nachvollziehbaren Betrieb

---

# Warum wird das zum Souveraenitaets-Thema?

- Ein Managed Service muss nicht nur sicher sein, sondern belegbar beherrschbar
- Datenhoheit ohne Betriebs-Observability bleibt unvollstaendig
- Souveraenitaet betrifft daher Plattform, Prozesse und Telemetrie
- Ohne O11y ist ein Managed Service auf einer souveraenen Plattform nicht glaubwuerdig

---
layout: section

---
# Tool-Auswahl und Dynatrace-Entscheidung

---
# Tooling-Landschaft

- Open Source, SaaS, Hybrid und Vendor Suites
- Unterschiedliche Staerken bei UX, Datenmodell, Automation und Enterprise-Funktionen
- Auswahl war kein Default, sondern eine bewusste Abwaegung
- Entscheidungskriterien gingen ueber Features deutlich hinaus

---
# Warum wir Dynatrace gewaehlt haben

- Reifes Produkt fuer Enterprise-Observability
- Breite Abdeckung fuer Plattform, Anwendungen und Betrieb
- Gute Eignung fuer Managed-Service-Betrieb statt Einzelprojekt-Nutzung
- Differenzierung nicht nur technisch, sondern auch als vermarktbarer Service

---
layout: section
---

# Kapitel 4

# USP finden

---

# BYOK als moeglicher USP

- Bring Your Own Key als Souveraenitaets-Baustein
- Relevanz fuer Trust, Compliance und Datenhoheit
- Untersuchung: Was ist technisch und betrieblich realistisch?
- Produktfrage: Wo entsteht echter Mehrwert statt nur Feature-Checkliste?

---
# Produktdifferenzierung statt Feature-Liste

- Ein USP muss technisch glaubwuerdig und operativ tragfaehig sein
- Nicht jede Plattform- oder Security-Funktion taugt als Produktmerkmal
- Interessant ist, was fuer Kunden echten Governance- und Vertrauenswert schafft
- BYOK war deshalb nicht nur Technik-Experiment, sondern Produktforschung

---

# Traffic

geht nirgends anders hin

---
layout: section
---

# Marketplace

---

# Vom Tool zum Produkt

- Zielbild: Dynatrace als Managed Service auf dem STACKIT Marketplace
- Nicht nur Installation, sondern Betriebsmodell, Support und Consumption
- Produktisierung verlangt Standardisierung ohne Verlust der Flexibilitaet
- Marketplace-Kontext bringt technische und kommerzielle Randbedingungen mit

---

# Pricing und Consumption Issues

- Consumption muss fuer Kunden nachvollziehbar und steuerbar sein
- Pricing passt nicht automatisch zu Plattform- und Marketplace-Modellen
- Technische Architektur wird durch Abrechnung und Mandantenfaehigkeit beeinflusst
- Monetarisierung ist kein Nachgedanke, sondern Architekturtreiber

---
layout: section
---

# SRE

---

# SRE-Ansatz und Automatisierung

- Dynatrace ist kein klassisches SRE-first Produkt aus eigener Entwicklung
- Trotzdem braucht der Service SLO-Denken, Runbooks, Automatisierung und Incident-Lernen
- Terraform fuer Infrastruktur und Standard-Workflows
- Ansible fuer Luecken, Day-2-Operationen und verfahrene Produktstellen

---

# Quirks, Networking und Support

- ALB-Funktionalitaet gab es nur via API, nicht ueber Terraform
- API Gateway wurde auch fuer monetarisierte APIs und Environment-Routing relevant
- Netzwerktrennung und Environment-Grenzen beeinflussten das Betriebsmodell direkt
- Support war schnell und gut, trotz mehrerer technischer Issues im Aufbau

---
layout: section
---

# Ausblick

---

# Wiederverwendbare Muster

- Dynatrace ist nicht Endpunkt, sondern Blaupause
- Aufbau von Betriebs-, Marketplace- und Automation-Patterns fuer weitere Services
- Wiederverwendbare Bestandteile: Provisioning, Routing, Consumption, Supportmodell

---

# Welche Services folgen?

- Die Architektur- und Betriebsprinzipien lassen sich auf weitere Produkte uebertragen
- Interessant sind Services mit aehnlichen Anforderungen an Souveraenitaet und Betriebsreife
- Marketplace und Managed Operations werden zur wiederholbaren Plattformfaehigkeit
- Abschlussfrage: Welche weiteren Managed Services profitieren von demselben Ansatz?

---

# Kernaussagen

- Observability ist technische und organisatorische Voraussetzung fuer Souveraenitaet
- Die Tool-Auswahl war ein Produkt- und Betriebsentscheid, nicht nur ein Feature-Vergleich
- Marketplace, Consumption und Security beeinflussen die Architektur direkt
- SRE-Prinzipien und starke Automation kompensieren viele Produktgrenzen

---
layout: end
---

# Danke

Fragen?
