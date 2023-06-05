---
title: Infrastructure Immuable
status: Completed
category: property
tags: ["infrastructure", "property", ""]
---

Une infrastructure immuable fait référence à une infrastructure informatique
([machines virtuelles](/virtual-machine/), [conteneurs](/container/), dispostifs réseau)
qui ne peut pas être modifiée une fois déployée.
Cela peut être imposé par un processus automatisé qui écrase les modifications non autorisées ou
grâce à un système conçu pour ne pas permettre de changements.
Les conteneurs sont un bon exemple d'infrastructure immuable car les modifications persistantes des conteneurs ne sont possibles qu'en créant une nouvelle version du conteneur ou en recréant le conteneur existant à partir de son image.

En empêchant ou en identifiant les modifications non autorisées, les infrastructures immuables facilitent l'identification et la diminution des risques de sécurité.
L'exploitation d'un tel système devient beaucoup plus simple car les administrateurs savent que personne n'a fait d'erreurs ou de changements qu'ils ont oublié de communiquer.
L'infrastructure immuable va de pair avec [l'infrastructure en tant que code](/infrastructure-as-code/) où toute l'automatisation nécessaire à la création de l'infrastructure est stockée dans le un gestionnaire de version (par exemple, Git).
Cette combinaison d'immuabilité et de gestion des versions signifie qu'il existe un journal d'audit robuste de chaque modification autorisée d'un système.
