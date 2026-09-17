# Data dictionary

This page describes the intended **public-release fields**. Internal curation fields, temporary review links, and QA notes are not part of the public schema.

| Field | Meaning |
|---|---|
| `Records ID` | Stable record identifier within the dataset |
| `Beetle Host` | Bark or ambrosia beetle host taxon |
| `pathogens` | Reported pathogen or parasite taxon/name |
| `categories` | Broad organism category: fungi, bacteria, viruses, nematodes, protists, or microsporidia |
| `country or region` | Study location as standardized from the source |
| `ecological relationship` | Relationship terminology reported or interpreted from the source under the project rules |
| `validation type` | Reported experimental validation, such as pathogenicity, virulence, infection, or transmission testing |
| `experimental conditions` | Laboratory, field, laboratory-and-field, or other reported experimental context |
| `identification method` | Morphological, molecular, combined, or not stated |
| `infection site` | Reported infection or localization site when available |
| `organism source` | Source of the tested or detected organism/isolate |
| `source` | Short-form literature citation |
| `title` | Full bibliographic citation/title field used for source traceability |
| `year` | Publication year |

## Public/internal separation

The public release will **not** include internal review URLs, temporary full-text links, private curation notes, or workflow-only QA fields.

## Interpretation cautions

- A row is a literature-derived association, not an independent biological replicate.
- Detection or isolation does not by itself prove active infection, pathogenicity, or causation.
- Record counts should not be interpreted as prevalence.
- Geographic values identify study locations, not complete pathogen distributions.
- Taxonomic standardization does not imply specimen re-identification.

The final v1.0 data dictionary will be synchronized with the frozen release schema after QA/QC is complete.
