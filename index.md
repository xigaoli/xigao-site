---
title: Xigao (Drake) Li
# subtitle: A system repairer, dataset wizard, Email troubleshooter, website ninja. probably a programmer. An apple a day keeps doctoral degree away.
layout: page
hero_height: is-small
# callouts: home_callouts
description: A system therapist, dataset wizard, Email troubleshooter, website ninja. probably a programmer. An apple device a day keeps doctoral degree away.
image: /img/xigao_2031_sq.png
show_sidebar: false
---

<style>
  .text-wrapper {
    max-width: 600px;
    font-size: 24px;
    font-style: italic;
    font-weight: bold;
  }
  .profile-img-container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .image-quote {
    font-style: italic;
    font-weight: bold;
  }

  .publication-head {
    background-color: rgba(76,175,80,0.2); /* Green background */
    color: white; /* White text */
    font-weight: bold;
    font-family: "Arial", "Helvetica", sans-serif; /* Clean, readable font */
    padding: 4px 10px; /* Add padding for spacing */
    border-radius: 8px; /* Rounded corners */
    display: inline-block; /* Ensures padding and background wrap properly */
    font-size: 14px; /* Adjust font size */
    text-transform: uppercase; /* Make text uppercase for emphasis */
}

  .span-news-head {
    background-color: rgba(76,175,80, 0.3); /* Green background */
    color: Black; /* White text */
    font-weight: bold;
    font-family: "Arial", "Helvetica", sans-serif; /* Clean, readable font */
    padding: 0px 6px; /* Add padding for spacing */
    border-radius: 8px; /* Rounded corners */
    display: inline-block; /* Ensures padding and background wrap properly */
    font-size: 14px; /* Adjust font size */
}

  .news-box {
      height: 200px; /* Fixed height to limit space usage */
      border: 1px solid #ccc; /* Light gray border for visibility */
      border-radius: 10px; /* Rounded corners */
      padding: 10px;
      overflow-y: auto; /* Enable vertical scrolling */
      font-family: Arial, sans-serif;
      font-size: 14px;
      line-height: 1.5; /* Improve readability */
  }
  /* Styles for the modal */
        .modal {
            display: none; /* Hidden by default */
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(57, 57, 57, 0.5);
        }

        .modal-content {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            width: 70%;
            max-width: 800px;
            margin: 15% auto;
            position: relative;
            text-align: center;
        }

        .close-btn {
            background: lightgrey;
            color: black;
            border: none;
            padding: 8px 16px;
            cursor: pointer;
            border-radius: 4px;
            margin-top: 10px;
            font-family: "SF Mono", "Menlo", "Consolas", "Courier New", monospace;
        }

        .copy-btn {
            background: lightgreen;
            color: black;
            border: none;
            padding: 8px 16px;
            cursor: pointer;
            border-radius: 4px;
            margin-top: 10px;
            font-family: "SF Mono", "Menlo", "Consolas", "Courier New", monospace;
        }

        textarea {
            width: 100%;
            height: 120px;
            resize: none;
            font-family: "SF Mono", "Menlo", "Consolas", "Courier New", monospace;
            background-color: #f5f5f5; /* Light gray background for better contrast */
            border: 1px solid #ccc;
            padding: 8px;
            color: #333333;
        }
        .hidden-reference {
            display: none;
        }
      /* button styles */
      .reference-btn {
        background-color: rgba(102, 236, 107, 0.3); /* Same green with 20% opacity */
        border: 2px solid rgba(192, 245, 194, 0.1); /* Subtle green border */
        color: #2d6a2d; /* Dark green text, same as span */
        font-family: "Arial", "Helvetica", sans-serif;
        padding: 4px 4px; 
        border-radius: 6px; 
        font-size: 10px;
        cursor: pointer;
        text-transform: uppercase; /* Optional: makes it stand out */
        transition: all 0.3s ease-in-out;
        display: inline-block;
      }

      .reference-btn:hover {
          background-color: rgba(76, 175, 80, 0.7); /* Slightly stronger green on hover */
          border-color: rgba(76, 175, 80, 0.7); /* Darken border slightly */
      }


</style>

<!-- The Modal to display reference -->
<div id="referenceModal" class="modal">
    <div class="modal-content">
        <h3>Reference</h3>
        <textarea id="referenceText" readonly>
--        
        </textarea>
        <br>
        <button class="copy-btn" onclick="copyReference()">Copy</button>
        <button class="close-btn" onclick="closeModal()">Close</button>
    </div>
</div>

<script>
function openModal(referenceId) {
            let referenceText = document.getElementById(referenceId).innerText.trim();
            document.getElementById("referenceText").value = referenceText;
            document.getElementById("referenceModal").style.display = "block";
        }
        function closeModal() {
            document.getElementById("referenceModal").style.display = "none";
        }
        function copyReference() {
            let textArea = document.getElementById("referenceText");
            textArea.select();
            textArea.setSelectionRange(0, 99999); // For mobile devices
            navigator.clipboard.writeText(textArea.value);
            alert("Reference copied!");
        }
</script>

<div class="columns">
  <div class="column is-6">
    <div class="text-wrapper">
      <p>A system therapist, dataset wizard, Email troubleshooter, website ninja.</p>
      <br>
      <p>And just maybe, a programmer. </p>
    <br>
    <br>
    </div>
  </div>
  <div class="profile-img-container">
    <img src="img/xigao_2031_sq.png" alt="Profile Image" width="300px">
    <p class="image-quote">"An apple device a day keeps doctoral degree away."</p>
  </div>
</div>

# News
<p> Last update: Feb 6, 2025</p>
<div class="news-box">

<span class="span-news-head">Paper accepted in WWW 2025!</span> [The Poorest Man in Babylon: A Longitudinal Study of Cryptocurrency Investment Scams](#news)
<button class="reference-btn" onclick="openModal('ref-muzammil2025crimson')">Reference</button>
<span id="ref-muzammil2025crimson" class="hidden-reference">
  @inproceedings{muzammil2025crimson,
    title = {The Poorest Man in Babylon: A Longitudinal Study of Cryptocurrency Investment Scams},
    author = {Muhammad Muzammil and Abisheka Pitumpe and Xigao Li and Amir Rahmati and Nick Nikiforakis},
    booktitle = {Proceedings of the Web Conference (WWW)},
    year = {2025},
  }
</span>
<br>

<span class="span-news-head">New Career!</span> <span>I have started my career in Meta as a Research Scientist, I work in internationalization (i18n) team, helping to deliver Meta products globally with a local feeling.</span> 
<br>

<span class="span-news-head">New Career!</span> <span>I have started my career in Bloomberg as a Software Engineer. My work will primarily support internal ticketing pipeline to ensure timely and accurate ticket generation and delivery.</span> 
<br>

<span class="span-news-head">Paper accepted in NDSS 2024!</span> [Like, Comment, Get Scammed: Characterizing Comment Scams on Media Platforms](https://like-comment-get-scammed.github.io/)
<button class="reference-btn" onclick="openModal('ref-li2024commentscams')">Reference</button>
<span id="ref-li2024commentscams" class="hidden-reference">
  @inproceedings{li2024commentscams,
    title = {Like, Comment, Get Scammed: Characterizing Comment Scams on Media Platforms},
    author = {Xigao Li and Amir Rahmati and Nick Nikiforakis},
    booktitle = {Proceedings of the Network and Distributed System Security Symposium (NDSS)},
    year = {2024},
  }
</span>
<br>

<span style="color:LightSalmon">I have successfully defended my Ph.D thesis, “Measuring the Role of Automation in Malicious Web Activities” on August 4th, 2023. </span>
<br>

<span class="span-news-head">Paper accepted in WWW 2023!</span> [Scan Me If You Can: Understanding and Detecting Unwanted Vulnerability Scanning](https://scan-me-if-you-can.github.io)
<button class="reference-btn" onclick="openModal('ref-li2023scanme')">Reference</button>
<span id="ref-li2023scanme" class="hidden-reference">
  @inproceedings{li2023scanme,
    author = {Li, Xigao and Amin Azad, Babak and Rahmati, Amir and Nikiforakis, Nick},
    title = {Scan Me If You Can: Understanding and Detecting Unwanted Vulnerability Scanning},
    year = {2023},
    booktitle = {Proceedings of the ACM Web Conference (WWW)},
    }
</span>
<br>

<span class="span-news-head">Paper accepted in NDSS 2023!</span> [Double and Nothing: Understanding and Detecting Cryptocurrency Giveaway Scams](https://double-and-nothing.github.io/)
<button class="reference-btn" onclick="openModal('ref-li2023cryptoscams')">Reference</button>
<span id="ref-li2023cryptoscams" class="hidden-reference">
  @inproceedings{li2023cryptoscams,
    title = {Double and Nothing: Understanding and Detecting Cryptocurrency Giveaway Scams},
    author = {Xigao Li and Anurag Yepuri and Nick Nikiforakis},
    booktitle = {Proceedings of the Network and Distributed System Security Symposium (NDSS)},
    year = {2023},
   }
</span>
<br>

<span class="span-news-head">Paper Accepted at Oakland 2021!</span> [Good Bot, Bad Bot: Characterizing Automated Browsing Activity](https://you.stonybrook.edu/xigaoli/files/2021/04/goodbotbadbot_oakland2021.pdf)
<button class="reference-btn" onclick="openModal('ref-li2021botcharacterization')">Reference</button>
<span id="ref-li2021botcharacterization" class="hidden-reference">
  @inproceedings{li2021botcharacterization,
    title = {Good Bot, Bad Bot: Characterizing Automated Browsing Activity},
    author = {Xigao Li and Babak {Amin Azad} and Amir Rahmati and Nick Nikiforakis},
    booktitle = {Proceedings of the 42nd IEEE Symposium on Security and Privacy (IEEE S\&P)},
    year = {2021},
   }     
</span>
<br>
</div>

# About Me

I am a Ph.D graduated in the Department of Computer Science at Stony Brook University.

During my Ph.D, I am co-advised by Professor Nick Nikiforakis and Professor Amir Rahmati. My research focuses on web security and machine learning. On one side, I develop systems to measure and classify automated Internet bots through both machine-learning and heuristic approaches, capture malicious bot behaviors by developing “fingerprinting” techniques. On the other side, I aim to build lightweight and pragmatic deep learning models and use information retrieval techniques to get security insights.

Prior to Stony Brook, I worked on file system security and optimization. My work of disaster-tolerance of MooseFS can be found in here(github), as well as some [published paper](https://link.springer.com/article/10.1007/s11227-016-1902-9).

# Published Paper

<ol>
  <li>
    <span class="publication-head">[WWW 2025]</span> <a href="">[The Poorest Man in Babylon: A Longitudinal Study of Cryptocurrency Investment Scams]</a>
    <button class="reference-btn" onclick="openModal('ref-muzammil2025crimson')">Reference</button>
    <span id="ref-muzammil2025crimson" class="hidden-reference">
      @inproceedings{muzammil2025crimson,
        title = {The Poorest Man in Babylon: A Longitudinal Study of Cryptocurrency Investment Scams},
        author = {Muhammad Muzammil and Abisheka Pitumpe and Xigao Li and Amir Rahmati and Nick Nikiforakis},
        booktitle = {Proceedings of the Web Conference (WWW)},
        year = {2025},
      }
    </span>
  </li>

  <li>
    <span class="publication-head">[NDSS 2024]</span> <a href="https://like-comment-get-scammed.github.io/">Like, Comment, Get Scammed: Characterizing Comment Scams on Media Platforms</a>
    <button class="reference-btn" onclick="openModal('ref-li2024commentscams')">Reference</button>
    <span id="ref-li2024commentscams" class="hidden-reference">
      @inproceedings{li2024commentscams,
        title = {Like, Comment, Get Scammed: Characterizing Comment Scams on Media Platforms},
        author = {Xigao Li and Amir Rahmati and Nick Nikiforakis},
        booktitle = {Proceedings of the Network and Distributed System Security Symposium (NDSS)},
        year = {2024},
      }
    </span>
  </li>

  <li>
    <span class="publication-head">[Thesis]</span> <a href="files/xigao-thesis-presentation-slides.pdf">Measuring the Role of Automation in Malicious Web Activities</a>
  </li>
  <li>
  <span class="publication-head">[WWW 2023]</span> <a href="https://scan-me-if-you-can.github.io">Scan Me If You Can: Understanding and Detecting Unwanted Vulnerability Scanning</a>
  <button class="reference-btn" onclick="openModal('ref-li2023scanme')">Reference</button>
  <span id="ref-li2023scanme" class="hidden-reference">
    @inproceedings{li2023scanme,
      author = {Li, Xigao and Amin Azad, Babak and Rahmati, Amir and Nikiforakis, Nick},
      title = {Scan Me If You Can: Understanding and Detecting Unwanted Vulnerability Scanning},
      year = {2023},
      booktitle = {Proceedings of the ACM Web Conference (WWW)},
      }
  </span>
  </li>
  
  <li>
  <span class="publication-head">[NDSS 2023]</span> <a href="https://double-and-nothing.github.io/">Double and Nothing: Understanding and Detecting Cryptocurrency Giveaway Scams</a>
  <button class="reference-btn" onclick="openModal('ref-li2023cryptoscams')">Reference</button>
  <span id="ref-li2023cryptoscams" class="hidden-reference">
    @inproceedings{li2023cryptoscams,
      title = {Double and Nothing: Understanding and Detecting Cryptocurrency Giveaway Scams},
      author = {Xigao Li and Anurag Yepuri and Nick Nikiforakis},
      booktitle = {Proceedings of the Network and Distributed System Security Symposium (NDSS)},
      year = {2023},
    }
  </span>
  </li>

  <li>
    <span class="publication-head">[Oakland 2021]</span> <a href="https://you.stonybrook.edu/xigaoli/files/2021/04/goodbotbadbot_oakland2021.pdf">Good Bot, Bad Bot: Characterizing Automated Browsing Activity</a>
    <button class="reference-btn" onclick="openModal('ref-li2021botcharacterization')">Reference</button>
    <span id="ref-li2021botcharacterization" class="hidden-reference">
      @inproceedings{li2021botcharacterization,
        title = {Good Bot, Bad Bot: Characterizing Automated Browsing Activity},
        author = {Xigao Li and Babak {Amin Azad} and Amir Rahmati and Nick Nikiforakis},
        booktitle = {Proceedings of the 42nd IEEE Symposium on Security and Privacy (IEEE S\&P)},
        year = {2021},
      }     
    </span>
  </li>
</ol>

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

<p>Lastly, I have something else that is interesting.</p>
<a href="https://quitphd.com"><img src="img/quit_cr.jpg" alt="Quit PhD" width="80px"></a>

[NA]: #

