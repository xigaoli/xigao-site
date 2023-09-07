---
title: Xigao Li
# subtitle: A system repairer, dataset wizard, Email troubleshooter, website ninja. probably a programmer. An apple a day keeps doctoral degree away.
layout: page
# callouts: home_callouts
# show_sidebar: false
---

<div class="columns">
  <div class="column is-6">
    <div class="text-wrapper" style="width: 400px;">
      "An apple device a day keeps doctoral degree away."
    </div>
  </div>
  <div class="column is-6">
    <img src="img/xigao_2031_sq.png" alt="Example image">
  </div>
</div>

# News
Last update: Dec 25, 2022

<span style="color:blue">Paper accepted in WWW 2023!</span> [Scan Me If You Can: Understanding and Detecting Unwanted Vulnerability Scanning][NA]

<span style="color:blue">Paper accepted in NDSS 2023!</span> [Double and Nothing: Understanding and Detecting Cryptocurrency Giveaway Scams](https://double-and-nothing.github.io/)

<span style="color:blue">Paper Accepted at Oakland 2021!</span> [Good Bot, Bad Bot: Characterizing Automated Browsing Activity](https://you.stonybrook.edu/xigaoli/files/2021/04/goodbotbadbot_oakland2021.pdf)


# About Me

I am a Ph.D candidate in the Department of Computer Science at Stony Brook University.

I am co-advised by Professor [Nick Nikiforakis](https://securitee.org/) and Professor [Amir Rahmati](https://amir.rahmati.com/). My research focuses on web security and machine learning. On one side, I develop systems to measure and classify automated Internet bots through both machine-learning and heuristic approaches, capture malicious bot behaviors by developing “fingerprinting” techniques. On the other side, I aim to build lightweight and pragmatic deep learning models and use information retrieval techniques to get security insights.

Prior to Stony Brook, I worked on file system security and optimization. My work of disaster-tolerance of MooseFS can be found in here(github), as well as some published paper.
[published paper](https://link.springer.com/article/10.1007/s11227-016-1902-9)

# Research Projects

* Understanding and Detecting Cryptocurrency Giveaway Scams (Paper Accepted at NDSS 2023!) [Paper website](https://double-and-nothing.github.io/)

  - First large-scale analysis over cryptocurrency giveaway scams.
  - Created automated cryptocurrency scam tracking systems to capture cryptocurrency scam webpages.
  - Collected 10,079 scam web pages in 6 months, extracted 2,266 cryptocurrency scam wallets.
  - Inititated first quantitative analysis to cryptocurrency scam fund loss – attackers have stolen the equivalent of tens of millions of dollars ($26M – $70M).

* Understanding and Detecting Unwanted Vulnerability Scanning (Paper Accepted at WWW 2023!)
  - Designed a testbed for web vulnerability scanners (WVS)
  - Observed differences between WVS and users though user study
  - Designed ScannerScope - supervised machine learning model classifies user vs. WVS

* Measuring Web Bot Ecosystem (Paper Accepted at Oakland 2021!) [Paper PDF](https://you.stonybrook.edu/xigaoli/files/2021/04/goodbotbadbot_oakland2021.pdf)

  - Created automatic systems that can deploy honeypot-like web servers to capture web bot activities.
  - Developed behavioral fingerprinting techniques to detect bot behavior and intention.
  - Analyzed bot behaviors, discover malicious bot intentions of bruteforcing, probing and exploiting vulnerabilities.
  - Created visualization of captured bot dataset, provide security insights.

* Malware Classification with Deep Neural Network using Lightweight Emulation [Talk PDF](https://www.camlis.org/s/camlis_2021_li.pdf)

  - Developed automated malware emulation pipeline, emulated 11 Million malwares with cost <10 hours for EMBER’17 dataset
  - Extracted malware API call sequence, memory access information and RWX counter
  - Trained lightGBM and character level CNN model, achieved 0.99 AUROC / 0.98 accuracy
  - Developed a hybrid CNN model classifying malware families, reached 0.96 accuracy

* Malicious URL detection for mobile browsers through Deep Neural Network 

  - Crawled both malicious and benign URLs from multiple sources
  - Trained a classifier through CNN and RNN(LSTM).
  - Make the model mobile-available, built a browser demo intergrated with ML model.


# Other Projects

Other than major research threads, I build mini-projects for testing new techniques and for fun.

* Animal breed classification with deep neural network [github](https://github.com/xigaoli/animal-breed-classification)

  - Trained a modified VGG16 model to classify cat/dog images and their specific breeds
  - Fine-tuned hyperparameters to achieve best accuracy.
  - Developed web app interface to classify animal breed from URL.

* Empirical study with time series data from Anime market [github](https://github.com/xigaoli/anime-ranking-trends)

  - Crawled anime ranking data from 2006 to 2021, extracted anime ranking and scoring data through websites, built a clean ranking dataset
  - Analyzed anime ranking trend, visualized with dynamic video [youtube video]
  - Analyzed popular anime picture tags through Safebooru, extracted popular tags from 2011 to 2021
  - Designed a decay algorithm to measure the popularity of tags over time.
  - Built and fine-tuned a multi-label classifier for anime figures based on a modified VGG-19 model; the model can predict possible tags from any anime figures.

* Anime face dataset and generation through generative adversarial network

  - Used face alignment technique to extract faces from ~30,000 anime portraits and ~2,500 cosplay human faces, build a anime-face oriented dataset.
  - Generated anime faces through styleGAN2, with aligned 15,000 anime faces through face detection.


* safebooru tag trend from 2010-2020:
 [https://you.stonybrook.edu/xigaoli/safebooru-anime-tag-trend-analysis/](https://you.stonybrook.edu/xigaoli/safebooru-anime-tag-trend-analysis/)
* Another mock personal homepage, but built through Wangler workers:
[https://my-worker.lxgfrom2009.workers.dev/](https://my-worker.lxgfrom2009.workers.dev/)
* Simple but pragmatic tool blocking SogouInput ads and tracking:
[https://github.com/xigaoli/sgcld](https://github.com/xigaoli/sgcld)

[NA]: #