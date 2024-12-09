---
description: >-
  Analyse de mauvaises configuration IaC et de vulnérabilités dans les packages
  opensource
---

# 2. Analyse de code

## Préambule

Cet exercice permet d'exécuter l'analyse de code pour illustrer l'approche `Shift Left.`

## Pré-requis

Les outils suivants doivent être installés sur votre poste de travail:

* Docker (via Docker Desktop)
* Git
* VSCode

## Extensions pour VSCode

### Prisma Cloud (Palo Alto Networks)

Cette extension est utile pour réaliser l'analyse de code directement depuis l'IDE VS Code.

Elle est disponible sur la marketplace de Microsoft 👉 [https://marketplace.visualstudio.com/items?itemName=PrismaCloud.prisma-cloud](https://marketplace.visualstudio.com/items?itemName=PrismaCloud.prisma-cloud)

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

Cette extension permet d'utiliser la version opensource de checkov (moteur d'analyse de code de Prisma Cloud). En version opensource, il n'est pas possible de d'exécuter l'analyse de vulnérabilités dans les packages opensource, communément appelé Software Composition Analysis (SCA).

### Trivy (Aqua Security)

Cette extension est utile pour réaliser l'analyse de code directement depuis l'IDE VS Code.

Elle est disponible sur la marketplace de Microsoft 👉 [https://marketplace.visualstudio.com/items?itemName=AquaSecurityOfficial.trivy-official](https://marketplace.visualstudio.com/items?itemName=AquaSecurityOfficial.trivy-official)

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

Trivy étant complètement opensource, cette extension permet de faire l'analyse IaC et SCA.
