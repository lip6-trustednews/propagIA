# Datacard — PROPAGIA

# The PROPAGIA dataset

This repository contains the PROPAGIA dataset, a collection of press-like French articles originating from web sources reported by VIGINUM and Recorded Future for media impersonation. These sources were flagged as using generative AI to produce propaganda as part of the STORM-1516/CopyCop influence campaign.

- **Nom du dataset** : PROPAGIA
- **Version** : v1.0
- **Conditions légales de partage** : Licence académique / recherche (usage non commercial, recherche uniquement). *À préciser : nom exact de la licence (ex. CC BY-NC 4.0, licence interne, etc.) si une licence formelle doit être référencée.*

### Description des données
- **Volume** : 2 646 articles
- **Sources** : 84 sites web impliqués dans des cas d'usurpation de médias (media impersonation)
- **Langue** : Français
- **Thématiques** : Articles de type presse liés à la campagne d'influence STORM-1516/CopyCop, signalés par VIGINUM et Recorded Future pour usage d'IA générative dans la production de propagande
- **Fenêtre de collecte** : du 1er décembre 2024 au 1er décembre 2025 (article le plus ancien : 2024-12-08 ; article le plus récent : 2025-12-01)

### Informations techniques
- **Format** : fichier JSON unique
- **Structure** : une ligne par article, avec les champs suivants

| Champ     | Description                          |
| --------- | ------------------------------------ |
| `source`  | Nom du site web publiant l'article   |
| `url`     | Lien direct vers l'article original  |
| `date`    | Date de publication                  |
| `title`   | Titre de l'article                   |
| `content` | Texte de l'article                   |

### Date de création
7 janvier 2026

### Contact associé
SAINERO Lila, lila.sainero@lip6.fr
ICARD Benjamin, benjamin.icard@lip6.fr

## Details

The dataset comprises 2,646 articles from 84 sources involved in media impersonation. The collection window spans December 1, 2024 to December 1, 2025. The earliest collected article is dated 2024-12-08, and the latest is 2025-12-01. Here is a plot showing a description of PROPAGIA and the distribution of the total number of articles per source.
![Website distribution](https://github.com/lip6-trustednews/propagIA/blob/main/website_distribution.png)
