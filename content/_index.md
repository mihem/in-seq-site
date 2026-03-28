---
# Leave the homepage title empty to use the site title
title:
date: 2025-08-23
type: landing

sections:
  - block: hero
    content:
      title: Welcome to the <br> Human PNS Atlas
      image:
        filename: scheme_manuscript.jpg
      text:

  - block: markdown
    content:
      title:
      text: |
        A large-scale single-cell transcriptional and spatial atlas of human peripheral nerves in health and disease (polyneuropathies). Interactive visualizations of the snRNA-seq and Xenium spatial transcriptomics data are available below.

        {{< icon name="book-open" pack="fas" >}} **Publication** — [Multi-omic identification of perineurial hyperplasia and lipid-associated nerve macrophages in human polyneuropathies](https://doi.org/10.1038/s41467-025-62964-8), Heming et al., *Nature Communications*, 2025

        {{< icon name="code" pack="fas" >}} **Code** — [GitHub](https://github.com/mihem/sural_atlas) | archived on [Zenodo](https://zenodo.org/records/15750104)

        {{< icon name="database" pack="fas" >}} **Raw data** — GEO [GSE285983](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE285983) | [GSE285984](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE285984)

        {{< icon name="chart-bar" pack="fas" >}} **Reproducibility** — [Quarto document](https://mihem.github.io/pns_atlas/) with automatic data download from Zenodo

  - block: collection
    id: datasets
    content:
      title: Datasets
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: datasets
    design:
      view: showcase
      columns: '1'
      flip_alt_rows: false

  - block: markdown
    id: contact
    content:
      title: Contact
      text: |
        If you have any questions, please contact us via [mheming.com](https://www.mheming.com).
---