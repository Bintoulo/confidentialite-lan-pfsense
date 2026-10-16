# Mise en place d'une solution de confidentialité dans un LAN

Rapport de fin de cycle de la **Licence professionnelle Réseaux Informatiques** (ISI, Dakar), année académique 2024-2025.

## Description
Conception et déploiement d'une architecture réseau sécurisée garantissant que seules les entités autorisées accèdent aux informations sensibles d'un réseau local, en combinant contrôle d'accès, chiffrement des communications et supervision de la sécurité.

## Ce qui a été réalisé
- Conception de l'architecture de confidentialité et établissement du budget
- Routage inter-VLAN et agrégation de liens (LACP / LAGG) pour la redondance
- Pare-feux **pfSense** : haute disponibilité avec synchronisation de configuration, interface web sécurisée en HTTPS
- **Suricata** (IDS/IPS) sur pfSense
- Tunnel **OpenVPN** avec ProtonVPN depuis pfSense
- Chiffrement de disque (**LUKS**) et tunnel **WireGuard** entre les serveurs
- **PostgreSQL** et gestion d'identité **FreeIPA**
- Serveur web en **HTTPS (TLS)**
- Supervision avec le SIEM **Wazuh** et déploiement des agents

## Technologies
pfSense, Suricata, OpenVPN, WireGuard, LUKS, PostgreSQL, FreeIPA, Wazuh, VLAN, LACP

## Contenu du dépôt
- `docs/RAPPORT_SOUTENANCE.pdf` : rapport complet (93 pages)

## Auteures
Bintou LO et Ndeye Marieme DIALLO

Encadrant : M. Racine Oumar SALL
