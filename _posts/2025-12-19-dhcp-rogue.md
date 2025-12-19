---
layout: single
title: "Lab Cybersécurité : Protection du réseau contre un DHCP Rogue"
date: 2025-12-18
description: "Mise en place de DHCP Snooping pour bloquer les serveurs DHCP non autorisés."
categories: [Cybersecurite]
author_profile: true
---

## Objectif

Empêcher l’apparition de **serveurs DHCP non autorisés** sur le réseau local à l’aide du mécanisme **DHCP Snooping**.

---
## Environnement

- Plateforme : **EVE-NG**
- Switch : **Cisco**
- Postes : **VPC**
- Serveur DHCP : simulé

---

## Scénario

Un utilisateur malveillant branche un **serveur DHCP rogue** sur le réseau.
Les machines reçoivent de **fausses configurations IP**, permettant :
- interception de trafic
- attaques Man-in-the-Middle
- déni de service

---

