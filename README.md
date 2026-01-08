# The PROPAGIA dataset

This repository contains the PROPAGIA dataset, a collection of press-like French articles originating from web sources reported by VIGINUM and Recorded Future for media impersonation. These sources were flagged as using generative AI to produce propaganda as part of the STORM-1516/CopyCop influence campaign.

## Details

The dataset comprises 2,646 articles from 84 sources involved in media impersonation. The collection window spans December 1, 2024 to December 1, 2025. The earliest collected article is dated 2024-12-08, and the latest is 2025-12-01. Here is a plot showing a description of PROPAGIA and the distribution of the total number of articles per source.
![Website distribution](https://github.com/lip6-trustednews/propagIA/blob/main/website_distribution.png)


## Structure

Our dataset is provided as a single JSON file. Each row represents one article and includes the following fields:

| Field     | Description                         |
| --------- | ----------------------------------- |
| `source`  | Name of the publishing website      |
| `url`     | Direct link to the original article |
| `date`    | Publication date                    |
| `title`   | Article title                       |
| `content` | Article text                        |
