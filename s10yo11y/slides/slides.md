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

Dynatrace on STACKIT, managed by CGI.
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

CGI is a global IT consulting company with around 94,000 employees worldwide.

What makes CGI stand out is its combination of global scale and strength with a highly local delivery model: close to clients, close to teams, and close to execution.

---
layout: two-cols
---

## TOC

1. Observability basics
2. Why O11y matters for sovereignty
3. Tool selection and the Dynatrace decision
4. Finding a USP
5. Managed Service auf dem Marketplace
6. Operations, automation, and technical hurdles
7. Outlook on further services

::right::

### Out of scope

- Marketing
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

## What is observability?

Observability (O11y) is more than "just" monitoring.
It is a capability that mature IT organizations use deliberately.

Many data sources are combined to observe the overall system, or even the full IT landscape. The common "pillars" are:
* Logs
* Metrics
* Traces
* Topology, Events

The goal is to understand systems, not just to collect alerts.

Monitoring answers known questions - observability helps with unknown failure scenarios.

---
layout: image-left
image: images/o11y-activeexample.png
backgroundSize: contain
---

## Active and passive

Observability creates different views on systems through correlation and context.
These views can focus on very different concerns, for example:

* Explainability / diagnosis / post-mortems
* Performance or end-to-end request latency
* Detecting and handling anomalies
* Resilience Control

---
layout: image-right
image: images/lhca-stage1.png
backgroundSize: contain
---

## Paramount

Dass Observability von besonderer Wichtigkeit sein kann, zeigt sich schnell wenn man typische Angriffsszenarien simuliert.
This becomes obvious very quickly when you simulate common attack scenarios.
How would the following situation be detected?
* Suddenly many token requests
* A spike in service calls
* Failed authentication attempts
* Pods restarting chaotically, but no service outage

Without security context, these are disconnected events that might not even be noticed.

In the talk and lab [Live Hacking Cloud Architectures](https://www.youtube.com/watch?v=ZC1YwpwVlo0), we show typical scenarios and end with one core lesson.


---
layout: section

---

# O11y for Sovereignty

---
layout: image-right
image: images/o11y-europestrength.png
backgroundSize: contain
---

## Digital sovereignty

From politics to technical talks, one of the most relevant terms for IT experts right now is digital sovereignty. The EU Commission states:
> Europe must now strengthen its digital sovereignty and set standards, rather than following those of others – with a clear focus on data, technology and infrastructure.

_Digital sovereignty does not mean owning systems - it means being able to understand and influence their behavior at any time._

No observability → no control → no sovereignty.

---
layout: image-left
image: images/o11y-challenge.png
backgroundSize: contain
---

## A clear case: O11y platforms on EU cloud

Sovereign IT landscapes need observability platforms.
But in the context of data sovereignty, some tools make this difficult.

To match the growing sovereignty requirements of industries in the EU, observability platforms need to be hosted within the EU.
This is exactly what we want to address professionally as a managed service offering.

---
layout: image-right
image: images/o11y-platforms.png
backgroundSize: contain
---

## Tooling landscape

There are many good observability tools, especially in the open source ecosystem.
For our managed service offering, we initially focus on:
* commercial vendors with proper support contracts
* self-hosted options
* limited competition in public hosted offerings
* our own delivery capability in technology consulting
* broad coverage across platform, applications, and operations


---
layout: section

---

# Wanted on Marketplace: USP

---
layout: image-right
image: images/sales.png
backgroundSize: contain
---

## What do our customers need?

Now that we have the idea and a solid rationale, we need a USP.

<v-clicks>

- Data sovereignty for in-transit and at-rest data
- Traffic sovereignty
- Contract management
- Shared & Dedicated Offering

</v-clicks>

---
layout: image-left
image: images/deliveryteam.png
backgroundSize: contain
---

## And what do we need in service delivery?

To deliver a strong service, we need:

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

## The goal: marketplace observability integration

The capability matters, and the vendor market is broad.
We are aiming for a comprehensive integration of the STACKIT Marketplace into all relevant workloads and resources.

It is not "just" about installation, but also about the operating model, support, and consumption.
At the same time, a marketplace context introduces technical and commercial constraints.

---
layout: image-left
image: images/marketplace-comsumption.png
backgroundSize: contain
---

## Pricing and consumption

Dynatrace and similar tools use a mature and highly granular pricing model.
That is almost the opposite of a "monthly flat rate based on T-shirt sizes."

* Consumption must be understandable and controllable for customers
* Pricing does not automatically fit platform and marketplace models
* Technical architecture is influenced by billing and multi-tenancy

That also means the marketplace does not necessarily need to generate consumption insights itself.
Monetization is not an afterthought, but an architectural driver.

---
layout: section
---

# Service Delivery

---
layout: image-right
image: images/dt-teamchallenge.png
backgroundSize: contain
---

## SRE approach and automation

> Site Reliability Engineering (SRE)

A site is not a single server. It is a usable system made up of applications, infrastructure, and dependencies.
SRE ensures that this site runs reliably - measurable, automated, and with clear goals for availability and quality.

SRE can be done as a team discipline.
Such teams often work with Terraform, Ansible, GitOps, Kubernetes, service mesh, incident management, and on-call.

---
layout: image-left
image: images/dt-originalArch.png
backgroundSize: contain
---

## SRE for non-cloud-native software

Dynatrace is strong in both features and product design.

In its managed form, however, it is not a classic SRE@Cloud-first design.
The focus is likely on compatibility with most datacenters, more traditional setups, or even air-gapped environments.

Still, the service needs SLO thinking, runbooks, automation, and autoscaling.
That is something our team has to build on its own.

---
layout: image-right
image: images/dt-team.png
backgroundSize: contain
---

## Team

The challenge attracted a team with a wide range of seniority levels.
A mix of:
- Cloud Engineers
- Observability Consultants
- Architects

started onboarding into STACKIT and Dynatrace.

---
layout: image-left
image: images/dt-targetArch.png
backgroundSize: contain
---

## Architecture design

We designed an architecture that cleanly separates two operating models and covers two dimensions:

- Dedicated: strongly isolated customer or tenant setups
- Shared: for multiple customers, using a Dynatrace multi-tenant setup

Both designs assume that incoming traffic either enters STACKIT from the _outside_ or is emitted _internally_ from within STACKIT.

The API gateway can make routing decisions based on that distinction.
This is how we address traffic sovereignty.

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

## Quirks and support

The SRE team had to get familiar with the IaaS and PaaS components.
That included several surprises, for example:

- The Application Load Balancer was only available via API, not via Terraform
- KMS integration with common tooling
- Network separation and environment boundaries directly affected the operating model
- Dev tooling

---
layout: image-right
image: images/thesismax.png
backgroundSize: contain
---

# Research & Thesis

The BYOK topic was complex.
So complex that Max Strack wrote an entire research thesis on it.

> 
> The thesis investigates how a managed Dynatrace service on STACKIT can be operated more sovereignly using Bring Your Own Key.
> It evaluates encrypting the persistence layer via dm-crypt/LUKS and analyzes key control through STACKIT KMS.
> It compares dedicated and shared operating models with regard to security, compliance, and data sovereignty.
>

Max may give separate talks on this topic, so stay tuned :)

---
layout: image-right
image: images/cgiSTACKIT.png
backgroundSize: contain
---

## Outlook

Our codebase is designed as a foundation.
It works not only for Dynatrace, but also for additional managed services on STACKIT.

Next, we are focusing on the technical marketplace integration.

At the right time, CGI recently announced that we intend to offer:

- Dev tooling platform (for example Coder)
- API gateway (for example Gravitee.io)
- Event streaming (for example Kafka)

on STACKIT.

---
layout: image-left
image: images/dt-teamLooking.png
backgroundSize: contain
---

## Shoutout

Time to say thanks: a big shoutout to our team.
In a short time, they went from
> never having worked with Dynatrace or STACKIT

to

> DEV & PROD up and running

The fast support from STACKIT was equally strong.
We opened tickets with great enthusiasm and were impressed by how quickly bugs got fixed.

Now we only need customers...

Looking at you. #noSales

---
layout: image
image: images/finalSlide.png
backgroundSize: 95%
---
