# Awesome-Baggage-Management

# Top Baggage Management Tools Ecosystem

**Curated List of SaaS/Commercial Products & Open-Source GitHub Projects**  
*Focused on Baggage Handling Systems (BHS), Baggage Reconciliation Systems (BRS), Tracking, Sorting & Airport Logistics*  
**Last updated: August 2026**

This repository tracks notable **commercial platforms** and **open-source projects** for **Baggage Management**. These systems handle the full baggage lifecycle in airports — from check-in and screening through sorting, loading, reconciliation, tracking, and delivery — ensuring bags reach the correct aircraft and are reunited with passengers.

**Examples** include SITA Bag Manager, Beumer CrisBag, Vanderlande BAGWARE, Glidepath, Leonardo Airport BHS, Daifuku Airport, Brock Solutions, Siemens Logistics, Amadeus Baggage Reconciliation, and RESA BRS (the category leaders).

**Open-source emphasis**: This section is heavily expanded with available projects for baggage tracking prototypes, airport system demos, integration platforms, computer-vision detection, and related logistics tools. True production-grade open-source BHS/BRS platforms are rare due to the specialized, safety-critical, and hardware-integrated nature of airport baggage systems; most real-world deployments rely on commercial vendors.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[SITA Bag Manager](https://www.sita.aero/)**  
  Leading baggage management and reconciliation solution providing real-time tracking, bag-to-passenger matching, custody transfer, and IATA Resolution 753 compliance across the journey.

- **[Beumer CrisBag](https://www.beumergroup.com/)**  
  Advanced baggage handling and software control systems for high-capacity airports, covering sorting, tracking, and operational management.

- **[Vanderlande BAGWARE](https://www.vanderlande.com/)**  
  Comprehensive baggage handling software suite supporting sorting, early bag storage, reconciliation, and end-to-end process control.

- **[Glidepath](https://www.glidepathgroup.com/)**  
  Baggage handling systems and control software focused on reliable sorting, tracking, and airport logistics solutions.

- **[Leonardo Airport BHS](https://www.leonardo.com/)**  
  Integrated baggage handling and security screening solutions with associated control and management software.

- **[Daifuku Airport](https://www.daifuku.com/)**  
  Full baggage handling systems and software (including Airflow, WebbView, and related modules) for sorting, tracking, and operational oversight.

- **[Brock Solutions](https://www.brocksolutions.com/)**, **[Siemens Logistics](https://www.siemens-logistics.com/)**, **[Amadeus Baggage Reconciliation](https://amadeus.com/)**, **[RESA BRS](https://www.resa.aero/)**  
  Additional strong platforms offering baggage reconciliation, handling control, tracking, and airport logistics software used by major airports and airlines worldwide.

## Open-Source GitHub Projects

- **[AirportSystems (AODB / BHS / DCS demos)](https://github.com/pgfernandez/AirportSystems)**  
  Educational/demo project implementing simplified Airport Operational Database (AODB), Baggage Handling System (BHS), and Departure Control System (DCS) components using modern web and messaging technologies.

- **[QR Baggage Tracking prototypes](https://github.com/rahulgv1905/qr-baggage-system)**  
  Open-source web applications demonstrating QR-code-based baggage tracking, scanning, and basic management workflows useful for smaller or research deployments.

- **[NABHAS Message Broker reference](https://github.com/DeX-Group-LLC)**  
  Reference implementations related to the North American Baggage Handling Architecture Standard (NABHAS) message broker for demonstration and testing of baggage messaging.

- **[Zato Airport Integration Platform](https://zato.io/en/industry/airports/)**  
  Open-source Python integration platform used to connect AODB, FIDS, baggage handling systems, airlines, and other airport systems in a unified, controllable architecture.

- **[Abandoned Baggage / Computer Vision projects](https://github.com/K-saif/Event-Driven-Abandoned-Baggage-Detection-System)**  
  Open-source real-time detection and tracking systems using computer vision (YOLO + DeepSORT) for person–bag association and abandoned baggage alerts in surveillance contexts.

- **[Open Logistics / Air Cargo initiatives](https://openlogisticsfoundation.org/)**  
  Community and foundation-driven open-source efforts around air cargo data exchange (e.g., IATA One Record implementations) that can intersect with broader baggage and logistics flows.

- **[AI workflow examples for baggage claims](https://github.com/)**  
  Open-source multi-agent frameworks and examples applied to damaged-baggage compensation and related airline operational workflows.

- **[General logistics & tracking platforms](https://github.com/)**  
  Broader open-source TMS and tracking systems that can be adapted for certain non-critical baggage or ground-handling visibility use cases.

### Additional Strong Open-Source Options

- Research and academic simulations of baggage flow, sorting algorithms, and airport logistics.
- Messaging and event-driven frameworks used to prototype BHS/BRS integrations.
- IoT and RFID/barcode scanning stacks that feed data into custom reconciliation logic.
- Many internal or regional airport IT prototypes that are partially released as open source.

**Frameworks for building custom systems**: Production airport BHS/BRS almost always require certified commercial hardware and software. For research, training, or lighter tracking needs, start with **demo/BHS prototypes**, use **Zato** or similar integration platforms to connect existing systems, apply **computer-vision projects** for security monitoring, and leverage open messaging standards (IATA BIX, NABHAS concepts, One Record) for data exchange. Full safety-critical sorting and high-speed diverters remain the domain of specialized vendors.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial/SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Airport baggage systems are safety-critical, highly regulated, and tightly integrated with physical infrastructure (conveyors, sorters, scanners, PLCs). Open-source components are primarily useful for prototyping, integration layers, research, training, or non-critical tracking. They do not replace certified commercial BHS/BRS solutions required for live airport operations.
- Always follow IATA resolutions (e.g., 753), local aviation authority requirements, and security standards when working with baggage data and systems.

---

**Made for airport IT teams, baggage system integrators, aviation software developers, and researchers exploring open approaches to baggage logistics.**  
Let's make airport technology more interoperable and transparent where possible.
