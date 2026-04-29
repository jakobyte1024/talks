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

How we built the service

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
layout: image-left
image: images/cgiOverview.png
backgroundSize: contain
---

## CGI

CGI ist ein globaler IT-Consulting-Konzern mit rund 94.000 Mitarbeitenden weltweit. 

Was CGI besonders macht: globale Stärke und Skalierung, kombiniert mit einem sehr lokalen Delivery-Modell – nah an den Kunden, nah an den Teams und nah an der Umsetzung.

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
layout: image-right
image: images/o11y-overview.png
backgroundSize: contain
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

---
layout: image-left
image: images/o11y-activeexample.png
backgroundSize: contain
---

## Aktiv und Passiv

Durch Observability entstehen Blickwinkel auf Systeme, durch Korrelation und Kontext.
Diese können verschiedenste Schwerpunkte haben, beispielsweise:

* Erklärbarkeit / Diagnose / Post-Mortem
* Performanz oder Durchlaufzeiten einer Request
* Anamolien beobachten und behandeln
* Resilience Control

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
* Fehlgeschlagene Authentifizierungen
* Pods starten offenbar chaotisch neu, jedoch kein Service Down

Ohne Security Context sind dies losgelöste Ereignisse, welche vielleicht gar nicht bemerkt werden.

Im Talk und Lab [Live Hacking Cloud Architectures](https://www.youtube.com/watch?v=ZC1YwpwVlo0) zeigen wir typische Szenarien und enden mit einer Weisheit.


---
layout: section

---

# O11y fuer Souveraenitaet

---
layout: image-right
image: images/o11y-europestrength.png
backgroundSize: contain
---

## Digitale Souveränität

Von der Politik hin zum Techtalk - einer der wichtigsten Begriffe für IT-Expert:innen ist aktuell wohl die Digitale Souveränität. Dazu sagt die EU Commision
> Europe must now strengthen its digital sovereignty and set standards, rather than following those of others – with a clear focus on data, technology and infrastructure.

_Digitale Souveränität bedeutet nicht, Systeme zu besitzen – sondern ihr Verhalten jederzeit nachvollziehen und beeinflussen zu können._

Keine Observability → Keine Kontrolle → Keine Souveränität.

---
layout: image-left
image: images/o11y-challenge.png
backgroundSize: contain
---

## Klarer Fall: O11y Plattformen auf EU Cloud 

Souveräne IT-Landschaften brauchen Observability Plattformen.
Doch im Spannungsfeld der Datenhoheit ist das mit manchen Tools schwierig.

Passend zu den wachsenden Befürdnissen nach digitaler Souveränität der Branchen in der EU braucht es in der EU gehostete Observability Plattformen.
Das möchten wir professionell als Managed Service Offering adressieren. 

---
layout: image-right
image: images/o11y-platforms.png
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

# Wanted on Marketplace: USP

---
layout: image-right
image: images/sales.png
backgroundSize: contain
---

## Was brauchen denn unsere Kunden?

Nun da wir die Idee und eine gute Begründung haben, brauchen wir einen USP.

<v-clicks>

- Datenhoheit über in-transit und at rest
- Traffic-Hoheit
- Vertragsmanagement
- Shared & Dedicated Offering

</v-clicks>

---
layout: image-left
image: images/deliveryteam.png
backgroundSize: contain
---

## Und was brauchen wir in der Service-Delivery?

Damit wir einen guten Service liefern

<v-clicks>

- Scalability by design
- Load & Performance Testing
- Staging
- Operational Readiness
</v-clicks>

---
layout: image-right
image: images/marketplaceO11dsol.png
backgroundSize: contain
---

## Das Ziel: Marketplace Observability Integration

Die Fähigkeit ist wichtig und der Anbietermarkt groß.
Wir denken an eine umfangreiche Integration des STACKIT Marketplace in alle passenden Workloads und Ressourcen.

Nicht "nur" Installation, sondern Betriebsmodell, Support und Consumption
Doch ein Marketplace-Kontext bringt technische und kommerzielle Randbedingungen mit.

---
layout: image-left
image: images/marketplace-comsumption.png
backgroundSize: contain
---

## Pricing und Consumption

Dynatrace und ähnliche Tools nutzen ein ausgereiftes und feingranulares Preismodell.
Das ist nahezu das Gegenteil zu "monatlicher Rate auf Basis T-Shirt Sizes" 

- Consumption muss fuer Kunden nachvollziehbar und steuerbar sein
- Pricing passt nicht automatisch zu Plattform- und Marketplace-Modellen
- Technische Architektur wird durch Abrechnung und Mandantenfaehigkeit beeinflusst

Das heißt jedoch auch dass der Marketplace nicht zwingend Consumption Insights generieren muss.
Monetarisierung ist kein Nachgedanke, sondern Architekturtreiber

---
layout: section
---

# Service Delivery

---
layout: image-right
image: images/dt-teamchallenge.png
backgroundSize: contain
---

## SRE-Ansatz und Automatisierung

> Site Reliability Engineering (SRE)

Eine Site ist kein einzelner Server, sondern ein nutzbares System aus Anwendungen, Infrastruktur und Abhängigkeiten.
SRE sorgt dafür, dass diese Site zuverlässig läuft – messbar, automatisiert und mit klaren Zielen für Verfügbarkeit und Qualität.

SRE kann man im Team machen.
Solche Teams arbeiten oft mit Terraform, Ansible, GitOps, Kubernetes, Service Mesh, Incident Management, OnCall

---
layout: image-left
image: images/dt-originalArch.png
backgroundSize: contain
---

## SRE für Non-Cloud-Native

Dynatrace ist führend in Feature und Produktdesign.

In der Managed-Variante ist es kein klassisches SRE@Cloud-first Design.
Der Fokus liegt vermutlich auf Kompatibilität zu den meisten Datacenter ein eher klassisches oder gar Air-Gap Setup.

Trotzdem braucht der Service SLO-Denken, Runbooks, Automatisierung und Autoscaling.
Das muss unser Team nun selbst bauen.

---
layout: image-right
image: images/dt-team.png
backgroundSize: contain
---

## Team

An der Challenge war ein Team verschiedenster Senioritätsstufen interessiert.
Ein Mix
- Cloud Engineeers
- Observability Consultants
- Architekten

begannen mit der Einarbeitung in STACKIT und Dynatrace.

---
layout: image-left
image: images/dt-targetArch.png
backgroundSize: contain
---

## Architekturdesign

Wir haben uns eine Architektur überlegt, die zwei Betriebsmodelle sauber trennt und in zwei Aspekten denkt

- Dedicated: stark isolierte Kunden- oder Tenant-Setups
- Shared: für mehrere Kunden; mit Dynatrace Multi Tenant Setup

Beide Designs sind darauf ausgelegt dass eingehender Traffic _extern_ nach STACKIT kommt oder _intern_ aus STACKIT emittiert wird.

Das API Gateway kann basierend darauf Routing-Entscheidungen treffen.
Damit adressieren wir Traffic-Hoheit.

---
layout: image
image: images/dt-teamCode.png
backgroundSize: 95%
---

---
layout: image-left
image: images/dt-teamCode2.png
backgroundSize: contain
---

## Quirks und Support

Das SRE-Team hat die IaaS & PaaS Komponenten kennengelernt.
Dazu gehörten auch mehrere Überraschungen.
Beispielsweise:

- Application Loadbalancer gab es nur via API, nicht via Terraform
- KMS Integration mit gängigen Tools
- Netzwerktrennung und Environment-Grenzen beeinflussten das Betriebsmodell direkt
- Dev-Tooling

---
layout: image-right
image: images/thesismax.png
backgroundSize: contain
---

# Research & Thesis

Das BYOK Thema war komplex.
So komplex dass sogar eine ganze Forschungsarbeit von Max Strack dazu verfasst wurde

>
> Die Arbeit untersucht, wie ein Managed Dynatrace Service auf STACKIT mit Bring Your Own Key souveräner betrieben werden kann. 
> Dafür wird die Persistenzschicht per dm-crypt/LUKS verschlüsselt und die Schlüsselkontrolle über das STACKIT KMS betrachtet. 
> Verglichen werden Dedicated- und Shared-Betriebsmodelle hinsichtlich Sicherheit, Compliance und Datensouveränität.
>

Max wird dazu vielleicht eigene Talks geben, stay tuned :)

---
layout: image-right
image: images/cgiSTACKIT.png
backgroundSize: contain
---

## Ausblick

Unsere Codebase ist als Fundament ausgelegt.
Sie funktioniert für Dynatrace, als auch für weitere Managed Services auf STACKIT.

Als nächstes widmen wir uns der technischen Marketplace Integration.

Zeitlich passend hat CGI jüngst bekannt gegeben, dass wir beabsichtigen

- Dev-Tooling-Plattform (bspw. Coder)
- API Gateway (bspw. Gravitee.io)
- Eventstreaming (bspw. Kafka)

auf STACKIT anzubieten.

---
layout: image-left
image: images/dt-teamLooking.png
backgroundSize: contain
---

## Shoutout

Zeit sich zu bedanken: großer Shoutout an unser Team.
In wenigen von 
> noch nie mit Dynatrace oder STACKIT gearbeitet

zu

> DEV & PROD up and running

Ebenso gut war der schnelle Support von STACKIT.
Wir haben leidenschaftlich Tickets eröffnet und waren beeindruckt wie schnell Bugs behoben werden.

Jetzt fehlen nur noch Kunden...

Looking at you. #noSales

---
layout: end
---

# Danke

Fragen?
