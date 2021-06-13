---
slides: example
url_pdf: ""
summary: We propose OmniLytics, a blockchain-based secure data trading
  marketplace for machine learning applications.
url_video: ""
date: 2016-04-27T00:00:00Z
external_link: https://twitter.com/jiang12477214
url_slides: ""
title: Secure data market on blockchain
tags:
  - Federated Learning
links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/jiang12477214
image:
  caption: ""
  focal_point: Smart
url_code: ""
---
We propose OmniLytics, a blockchain-based secure data trading marketplace for machine learning applications. Utilizing OmniLytics, many distributed data owners can contribute their private data to collectively train a ML model requested by some model owners, and get compensated for data contribution. OmniLytics enables such model training while simultaneously providing 1) model security against curious data owners; 2) data security against the curious model and data owners; 3) resilience to malicious data owners who provide faulty results to poison model training, and 4) resilience to malicious model owner who intents to evade the payment. OmniLytics is implemented as a smart contract on the Ethereum blockchain to guarantee the atomicity of payment. In OmniLytics, a model owner publishes encrypted initial model on the contract, over which the participating data owners compute gradients using their private data, and securely aggregate the gradients through the contract. Finally, the contract reimburses the data owners, and the model owner decrypts the aggregated model update. We implement a working prototype of OmniLytics on Ethereum and perform extensive experiments to measure its gas cost and execution time under various parameter combinations, demonstrating its high computation and cost efficiency and strong practicality.