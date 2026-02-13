
# Sécurisation et intégration d’une infrastructure réseau multi-VLAN

## Contexte
Projet réalisé dans le cadre du module *Sécurité des réseaux*.
L’objectif était de concevoir, configurer et sécuriser une infrastructure réseau
d’entreprise simulée à l’aide de Cisco Packet Tracer.

## Objectifs techniques
- Segmenter le réseau via des VLANs
- Mettre en place le routage inter-VLAN
- Fournir l’accès Internet sécurisé aux hôtes internes
- Sécuriser l’administration des équipements réseau

## Travaux réalisés

### Architecture réseau
- Conception d’une topologie multi-sites (HQ, B1, B2)
- Segmentation logique par VLAN (PCs, serveurs, management)
- Plan d’adressage IPv4 structuré et documenté

### Configuration réseau
- VLANs, trunking 802.1Q
- Routage inter-VLAN (Router-on-a-Stick)
- DHCP pour les postes utilisateurs
- Routage dynamique RIPv2
- Route par défaut vers Internet

### Sécurité et contrôle des accès
- Mise en place du NAT (statique et PAT)
- Sécurisation de l’accès distant par SSH v2
- Port Security sur les ports sensibles
- Désactivation des interfaces inutilisées
- ACL pour le contrôle du trafic NAT

## Vérifications
- Tests de connectivité inter-VLAN
- Accès Internet fonctionnel depuis le LAN
- Connexion SSH sécurisée
- Vérification des traductions NAT

## Apports du projet
- Compréhension concrète des architectures réseau d’entreprise
- Maîtrise des mécanismes de segmentation, routage et sécurité
- Approche méthodique de la configuration et du dépannage réseau
- Importance de la documentation technique et de la traçabilité
