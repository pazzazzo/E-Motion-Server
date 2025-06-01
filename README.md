# E-Motion Server

E-Motion Server est le serveur visant à traiter des données importantes du dashboard tel que les connexions api, ou la gestion de vol.

## Objectifs

Les objectifs du serveurs sont les suivants:

- **Suivi des véhicules en temps réel :** Dans le cas où le véhicule serais perdu, les clients ou autoritées légales pourraient contacter le gérant du serveur afin de connaitre l'emplacement du véhicule ainsi que ses derniers trajets.
- **Connexions APIs :** Le serveur déliverais les URIs nécéssaires à la connexions à spotify.
- **Traitement de données :** Le serveur pourrait traiter les données clients dans le cadre d'une amélioration du service et de son extention au grand publique.

## Technologies

Le serveur utilise Socket.io

## Checklist

- [ ] Mettre en place une politique de confidentialité claire
- [ ] Obtenir un consentement explicite pour les traitements
- [ ] Sécuriser les transmissions et stockages (hashing, TLS, accès restreints)
- [ ] Effectuer une AIPD (analyse d’impact) RGPD
- [ ] Préparer la certification CE et conformité RED/LVD
- [ ] Changer de licence open source adaptée au logiciel
- [ ] Prévoir un système d’accès légal aux données en cas de vol
