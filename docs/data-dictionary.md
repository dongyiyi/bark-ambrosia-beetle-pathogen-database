# Data dictionary

This page describes the **Version 1.0 public fields**. Internal curation fields, temporary review links, and QA notes are not part of the public schema.

| Field | Meaning |
|---|---|
| `Records ID` | Stable record identifier within the dataset |
| `Beetle Host` | Bark or ambrosia beetle host taxon |
| `categories` | Broad organism category: fungi, bacteria, viruses, nematodes, protists, or microsporidia |
| `pathogens` | Reported organism taxon/name retained in the database |
| `country or region` | Study location as standardized from the source |
| `ecological relationship` | Relationship terminology reported or interpreted from the source under the project rules, including pathogen, parasite, associate, and related statuses |
| `experimental conditions` | Laboratory, field, laboratory-and-field, or other reported experimental context |
| `identification method` | Morphological, molecular, combined, or not stated |
| `infection site` | Reported infection or localization site when available |
| `organism source` | Source of the tested, isolated, or detected organism/isolate |
| `validation type` | Reported experimental validation, such as infection, pathogenicity, virulence, or transmission testing |
| `source` | Short-form literature citation |
| `year` | Publication year |
| `full text` | Availability or extent of source-text access used during curation, when recorded |
| `title` | Full bibliographic reference used for source traceability |

## Public/internal separation

The public release does **not** include internal review URLs, temporary private full-text links, private curation notes, or workflow-only QA fields.

## Interpretation cautions

- A row is a literature-derived association, not an independent biological replicate.
- An organism retained in the dataset is not automatically classified as a pathogen; ecological relationship is recorded separately.
- Detection, isolation, or association does not by itself prove active infection, pathogenicity, or causation.
- Record counts should not be interpreted as prevalence.
- Geographic values identify study locations, not complete organism distributions.
- Taxonomic standardization does not imply specimen re-identification.
