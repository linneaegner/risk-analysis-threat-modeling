# Risk Analysis and Threat Modeling

This repository contains a threat model and a risk analysis for a small business system that manages customers, orders and invoices.

The project was completed as part of an Information Security course.

## Objective

The objective was to identify information assets, model security threats using OWASP Threat Dragon, and perform a structured risk analysis based on likelihood and impact.

## System Overview

The business system consists of:

- Customer management
- Invoice system
- Database
- Cloud service
- Mobile devices used by field personnel
- External integration (Swedish Tax Agency)

## Methodology

The threat model was created using **OWASP Threat Dragon**.

Threats were identified using the system's trust boundaries and classified according to the **CIA triad**:

- Confidentiality
- Integrity
- Availability

The identified threats were then evaluated in a risk register based on:

- Likelihood (1–4)
- Consequence (1–4)
- Overall risk level

## Tools

- OWASP Threat Dragon
- Microsoft Excel

## Files

- `hotmodell-lineg196.json`
- `riskanalys-lineg196.xlsx`

## Screenshots

### Threat model

![Threat Model](screenshots/threat-model.png)

### Risk matrix

![Risk Matrix](screenshots/risk-matrix.png)
