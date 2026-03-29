---
# Leave the homepage title empty to use the site title
title:
date: 2026-03-28
type: landing

sections:
  - block: markdown
    content:
      title:
      text: |
        <img src="/media/scheme_manuscript.jpg" style="width:100%; height:auto;">

  - block: markdown
    content:
      title:
      text: |
        A single-cell transcriptional dataset of paired blood and cerebrospinal fluid from 24 polyneuropathy patients and 7 controls.

        {{< icon name="book-open" pack="fas" >}} **Publication** — unpublished

        {{< icon name="code" pack="fas" >}} **Code** — [GitHub](https://github.com/mihem/csf_pbmc_pnp_seq)

        {{< icon name="database" pack="fas" >}} **Raw data** — coming soon

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