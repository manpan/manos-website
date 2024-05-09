---
title: "Secure genotype imputation using homomorphic encryption"
authors: [Junwei Zhou, Botian Lei, Huile Lang, Emmanouil Panaousis, Kaitai Liang, Jianwen Xiang]
date: 2022-12-05
publishDate: 2023-02-01
publication_types: ["2"]
publication: "_Journal of Information Security and Applications_"
publication_short: "_JISA_, Vol. 72, pp. 103386"
doi: "https://doi.org/10.1016/j.jisa.2022.103386"
abstract: "Genotype imputation estimates missing genotypes from the haplotype or genotype reference panel in individual genetic sequences, which boosts the potential of genome-wide association and is essential in genetic data analysis. However, the genetic sequences involve people’s privacy, confirming an individual’s identification and even disease information. This work proposes a secure genotype imputation model, which uses a linear regression model and the homomorphic encryption scheme over ciphertext to impute missing genotypes. The inference model is trained with float plaintext parameters, which are round into integers to avoid high complexity homomorphic evaluation on float number operations without bootstrapping operations. Even though the rounding parameters in the inference model are not the same as those in the trained model, We find that it will no effect on the outcome of the homomorphic prediction. Thus, a high-efficiency genotype imputation inference model over the ciphertext is obtained while keeping the high-security level. The simulation results indicate that the accuracy of the secure inference model is almost the same as the original model trained on float parameters. The secure inference model’s accuracy is 98.6% for a single genotype."
tags: [privacy-preserving, homomorphic encryption, genotype imputation, privacy computing, genetic security]
categories: [Journal]
featured: false
url_pdf: "papers/zhou2022secure.pdf"
#url_code: ""
image:
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
#slides: ""
note: "(JCR 2021: 4.96, CiteScore 2021: 7.6)"
---
