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

### Citation

If you use this repository in your work, please cite the related paper:

Icard, B., Vuichard, E., Lefebvre, L., Sainero, L., Girault, T., Breton, A., Launay, T., Bourgne, G., Casanova, M., Gadek, G., Klötzer, V., Le Nouy, M., Gravier, G., Ganascia, J.-G., & Égré, P. (2026). Propaganda forensics: Recovering the generation pipeline of an AI-driven influence campaign. In *Proceedings of the 10th Workshop on Online Abuse and Harms (WOAH), EMNLP 2026*. Association for Computational Linguistics. To appear.

```bibtex
@inproceedings{icard2026propaganda,
  title     = {Propaganda Forensics: Recovering the Generation Pipeline of an AI-Driven Influence Campaign},
  author    = {Icard, Benjamin and Vuichard, Elouan and Lefebvre, Louis and Sainero, Lila and Girault, Thomas and Breton, Alice and Launay, Tanguy and Bourgne, Gauvain and Casanova, Morgane and Gadek, Guillaume and Klötzer, Victor and Le Nouy, Michel and Gravier, Guillaume and Ganascia, Jean-Gabriel and Égré, Paul},
  booktitle = {Proceedings of the 10th Workshop on Online Abuse and Harms (WOAH), EMNLP 2026},
  publisher = {Association for Computational Linguistics},
  year      = {2026},
  note      = {To appear},
  url       = {https://arxiv.org/abs/2608.15746}
}
```


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
| Sentences per article (mean) | 20.6 |
| Sentences per article (median) | 14.0 |
| Tokens per article (minimum) | 100 |
| Tokens per article (maximum) | 400 |

*The token minimum and maximum are the observed range of the collected articles, not an inclusion criterion.*

The plot below shows the distribution of the number of articles per source.

![Distribution of articles per source](https://raw.githubusercontent.com/lip6-trustednews/propagIA/main/website_distribution.png)
