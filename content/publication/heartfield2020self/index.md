---
title: "Self-Configurable Cyber-Physical Intrusion Detection for Smart Homes Using Reinforcement Learning"
authors: [Ryan Heartfield, George Loukas, Anatolij Bezemskij, Emmanouil Panaousis]
date: 2020-11-14
publishDate: 2020-11-14
publication_types: ["2"]
publication: "_IEEE Transactions on Information Forensics and Security_"
publication_short: "_IEEE TIFS_"
#doi: ""
abstract: "The modern Internet of Things (IoT)-based smart home is a challenging environment to secure: devices change, new vulnerabilities are discovered and often remain unpatched, and different users interact with their devices differently and have different cyber risk attitudes. A security breach's impact is not limited to cyberspace, as it can also affect or be facilitated in physical space, for example, via voice. In this environment, intrusion detection cannot rely solely on static models that remain the same over time and are the same for all users.
We present MAGPIE, the first smart home intrusion detection system that is able to autonomously adjust the decision function of its underlying anomaly classification models to a smart home's changing conditions (e.g., new devices, new automation rules and user interaction with them). The method achieves this goal by applying a novel probabilistic cluster-based reward mechanism to non-stationary multi-armed bandit reinforcement learning. MAGPIE rewards the sets of hyperparameters of its underlying isolation forest unsupervised anomaly classifiers based on the cluster silhouette scores of their output. Experimental evaluation in a real household shows that MAGPIE exhibits high accuracy because of two further innovations: it takes into account both cyber and physical sources of data; and it detects human presence to utilise models that exhibit the highest accuracy in each case. MAGPIE is available in open-source format, together with its evaluation datasets, so it can benefit from future advances in unsupervised and reinforcement learning and be able to be enriched with further sources of data as smart home environments and attacks evolve."
# summary: ""
tags: [Privacy]
categories: [Journal]
featured: false
url_pdf: "https://www.manospanaousis.com/papers/heartfield2020self.pdf"
url_code: "https://github.com/isec-greenwich/magpie"
image:
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
slides: ""
note: "(JCR 2019: 6.013)"

---
