# Dataset Card - PROPAGIA

# The PROPAGIA Dataset

This repository contains the PROPAGIA dataset, a collection of press-like French articles originating from web sources reported by VIGINUM and INSIKT GROUP for media impersonation. These sources were flagged as using generative AI to produce propaganda as part of the STORM-1516/CopyCop influence campaign.

- **Dataset Name**: PROPAGIA
- **Version**: v1.0
- **License / Sharing Terms**: CC BY 4.0

### Data Description

- **Size**: 2,646 articles
- **Sources**: 84 websites involved in media impersonation cases
- **Language**: French
- **Topics**: Press-style articles linked to the STORM-1516/CopyCop influence operation, flagged by VIGINUM and INSIKT GROUP for the use of generative AI in producing propaganda
- **Collection Window**: December 1, 2024 to December 1, 2025 (earliest article: 2024-12-08; latest article: 2025-12-01)

### Technical Information

- **Format**: single JSON file
- **Structure**: one entry per article, with the following fields

| Field     | Description                             |
| --------- | --------------------------------------- |
| `source`  | Name of the website publishing the article |
| `url`     | Direct link to the original article     |
| `date`    | Publication date                        |
| `title`   | Article title                           |
| `content` | Article text                            |

### Creation date

January 7, 2026

### Contact
SAINERO Lila, lila.sainero@lip6.fr
ICARD Benjamin, benjamin.icard@lip6.fr

## Details

The dataset comprises 2,646 articles from 84 sources involved in media impersonation.
The collection window spans December 1, 2024 to December 1, 2025: the earliest collected
article is dated 2024-12-08 and the latest 2025-12-01. The table below summarizes the
main corpus statistics.

| Statistic | Value |
|---|---:|
| Number of articles | 2,646 |
| Number of impersonating websites | 84 |
| Articles per website (mean) | 31.5 |
| Articles per website (median) | 25 |
| Tokens per article (mean) | 250.5 |
| Tokens per article (minimum) | 100 |
| Tokens per article (maximum) | 400 |
| Sentences per article (mean) | 20.6 |
| Sentences per article (median) | 14.0 |

*The token minimum and maximum are the observed range of the collected articles, not an inclusion criterion.*

The plot below shows the distribution of the number of articles per source.

![Distribution of articles per source](https://raw.githubusercontent.com/lip6-trustednews/propagIA/main/website_distribution.png)
