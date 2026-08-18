# Data documentation

This directory contains small, derived datasets created for the spatial analysis in
the course paper. It does not contain the complete source texts.

## Public derived files

| File | Description | Coverage |
| --- | --- | --- |
| `derived_public/achilles_iliad_spatial_mentions_public.xlsx` | Spatial mentions associated with Achilles in *The Iliad* | 50 data rows plus header |
| `derived_public/briseis_iliad_spatial_mentions_public.xlsx` | Spatial mentions associated with Briseis in *The Iliad* | 7 data rows plus header |
| `derived_public/briseis_sog_spatial_annotations_public.xlsx` | Manually annotated Briseis spaces in *The Silence of the Girls* | 66 annotation rows plus a space-count sheet |

These public workbooks support the character-movement visualizations. They contain
sentence identifiers and spatial classifications but omit the source-text sentence
columns found in the local research copies. They should be read as manually
constructed research data rather than as an exhaustive geographic gazetteer.

## Editions used

- Homer. *The Iliad*. Translated by Emily Wilson, 2023.
- Barker, Pat. *The Silence of the Girls*. Doubleday, 2018.

## Private source texts

The local research archive contains processed copies of the two source texts under
`data/raw_private/`, as well as fuller annotation workbooks containing source-text
excerpts. Those files are excluded by `.gitignore` and must not be committed to a
public repository.

## Known gaps

- The Achilles-in-*The Silence of the Girls* source annotation workbook has not
  been recovered.
- The KWIC/manual classification file underlying Figure 2.4 has not been recovered.
- The original analysis scripts and exact preprocessing environment remain to be
  reconstructed.

## Reuse note

Before redistributing these workbooks, inspect individual cells for short source-text
excerpts and consider the copyright and quotation rules that apply in your
jurisdiction. The datasets document the research process; the underlying literary
works remain the property of their respective rights holders.
