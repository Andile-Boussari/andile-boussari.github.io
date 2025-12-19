---
layout: single
title: "Lab Cybersécurité : Sécurisation des ports avec Port Security"
date: 2025-12-16
description: "Mise en place de Port Security pour limiter les accès non autorisés."
categories: [Cybersecurite]
author_profile: true
---

## Objectif

Renforcer la sécurité du réseau local en **limitant les équipements autorisés** sur les ports du switch.

---

## Environnement

- Outil : **EVE-NG**
- Switch : **Cisco**
- Postes : **VPC**
- Connexion : Ethernet

---

## Scénario

- Un PC autorisé est connecté sur un port
- Un second PC tente de se connecter sur le même port
- Le switch doit **bloquer automatiquement** l’accès

---

## Configuration du Switch

### Activation de Port Security

interface gi0/0
switchport mode access
switchport port-security
switchport port-security maximum 1
switchport port-security violation shutdown

``
Test
``