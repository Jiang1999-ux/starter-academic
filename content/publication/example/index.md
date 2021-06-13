---
abstract: We propose OmniLytics, a blockchain-based secure data trading
  marketplace for machine learning applications. Utilizing OmniLytics, many
  distributed data owners can contribute their private data to collectively
  train a ML model requested by some model owners, and get compensated for data
  contribution. OmniLytics enables such model training while simultaneously
  providing 1) model security against curious data owners; 2) data security
  against the curious model and data owners; 3) resilience to malicious data
  owners who provide faulty results to poison model training, and 4) resilience
  to malicious model owner who intents to evade the payment. OmniLytics is
  implemented as a smart contract on the Ethereum blockchain to guarantee the
  atomicity of payment. In OmniLytics, a model owner publishes encrypted initial
  model on the contract, over which the participating data owners compute
  gradients using their private data, and securely aggregate the gradients
  through the contract. Finally, the contract reimburses the data owners, and
  the model owner decrypts the aggregated model update. We implement a working
  prototype of OmniLytics on Ethereum and perform extensive experiments to
  measure its gas cost and execution time under various parameter combinations,
  demonstrating its high computation and cost efficiency and strong
  practicality.
slides: example
url_pdf: ""
publication_types:
  - "1"
authors:
  - Jiangcheng Liang
  - admin
  - Songze Li
author_notes:
  - Equal contribution
  - Equal contribution
publication: under review *ICML-FL*
summary: We propose OmniLytics, a blockchain-based secure data trading
  marketplace for machine learning applications.
url_dataset: ""
url_project: ""
publication_short: under review *ICML-FL*
url_source: ""
url_video: ""
title: OmniLytics A Blockchain-based Secure Data Market for Decentralized
  Machine Learning
doi: ""
featured: true
tags: []
projects:
  - example
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
  filename: featured.jpg.jpg
date: 2021-06-13T02:47:27.352Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
