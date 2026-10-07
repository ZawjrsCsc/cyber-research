---
layout: default
title: "CISA Guidance: Implementing Phishing-Resistant MFA"
date: 2026-10-07
tags: [cybersecurity]
---

# CISA Guidance: Implementing Phishing-Resistant MFA

## Overview

The Cybersecurity and Infrastructure Security Agency (CISA) strongly advocates for the adoption of phishing-resistant Multi-Factor Authentication (MFA) across all organization types. Traditional MFA methods, such as SMS codes, voice calls, and standard push notifications, remain vulnerable to adversary-in-the-middle (AiTM) phishing, domain spoofing, and MFA fatigue attacks.

## Core Phishing-Resistant Authenticators

Phishing-resistant authentication protocols rely on cryptographic proof tied directly to the specific web domain's origin. CISA identifies two key standards for robust protection:

* **FIDO2 / WebAuthn:** Cryptographic hardware security keys and platform authenticators that automatically bind authentication sessions to legitimate domain origins, preventing credential harvesting on spoofed websites.
* **PKI-Based Smart Cards:** Public Key Infrastructure (PKI) tokens and smart cards that use cryptographic digital certificates to authenticate user identity securely.

## Migration and Implementation Strategy

To transition effectively to a phishing-resistant MFA architecture, organizations should follow a structured approach:

1. **Prioritize High-Risk Roles:** Deploy hardware security keys or PKI authenticators immediately to IT administrators, executive staff, and users accessing critical enterprise infrastructure.
2. **Phase Out Legacy Authenticators:** Disable weak authentication factors such as SMS, email OTP, and unanchored push alerts.
3. **Enforce Conditional Access Policies:** Configure centralized Identity Providers (IdPs) to require phishing-resistant methods for all sensitive applications and remote connections.

## Sources

* [CISA: Implementing Phishing-Resistant MFA](/content/CISA_%20Implementing%20Phishing-Resistant%20MFA%20(1).url)
