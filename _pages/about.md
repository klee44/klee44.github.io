---
permalink: /
#title: "KLee personal website"
#excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an assistant professor in [School of Computing and Augmented Intelligence](https://scai.engineering.asu.edu/) at [Arizona State University](https://www.asu.edu/). My research focuses on scientific machine learning, including data-driven surrogate modeling for fluid dynamics and plasma physics, neural representations of scientific fields, and physics-informed and structure-preserving modeling of dynamical systems. My work has been supported by the National Science Foundation (NSF), Sandia National Laboratories, Salt River Project (SRP), Honeywell, Applied Materials, and Meta. I received the [NSF CAREER Award](https://www.nsf.gov/awardsearch/show-award?AWD_ID=2338909) in 2024 and the KOCSEA Young Faculty Award (K-YFA) in 2026. <br/> 

<!-- <b>Open positions</b>: I am looking for self-motivated Ph.D. research assistants. Email me with your CV and a brief introduction of your research interests to kookjin.lee@asu.edu. --> 


## Research Highlights

<!--### Structure-preserving dynamics modeling--> 
**Structure-preserving dynamics modeling:** Develop machine learning models that embed physical laws, such as energy conservation and entropy production, directly into their architecture for stable and reliable long-term prediction. [[NeurIPS 2021](https://proceedings.neurips.cc/paper/2021/file/2d1bcedd27b586d2a9562a0f8e076b41-Paper.pdf),[MSML 2022](https://proceedings.mlr.press/v190/lee22a/lee22a.pdf),[NeurIPS 2023](https://proceedings.neurips.cc/paper_files/paper/2023/file/7903af0a1cffb43dbb2f8160d110a5f3-Paper-Conference.pdf),[ICLR 2025](https://openreview.net/pdf?id=uL1H29dM0c),[TMLR 2026](https://openreview.net/pdf?id=Qy3oLpRzpf),[ICML 2026](https://arxiv.org/abs/2508.11205)] 
[Learn more →](/sp/)

**Implicit neural representations (INRs)/physics-informed neural networks (PINNs)**: Develop continuous neural function representations for complex and structured signals, enabling resolution-independent modeling and principled learning under known constraints. [[AAAI 2021](https://ojs.aaai.org/index.php/AAAI/article/view/16992/16799),[NeurIPS 2023](https://proceedings.neurips.cc/paper_files/paper/2023/file/24f8dd1b8f154f1ee0d7a59e368eccf3-Paper-Conference.pdf),[ICML 2024](https://raw.githubusercontent.com/mlresearch/v235/main/assets/cho24b/cho24b.pdf),[ICLR 2025](https://proceedings.iclr.cc/paper_files/paper/2025/file/678594bcff6f99f3b7a8ff459989b1a3-Paper-Conference.pdf),[NeurIPS 2025](https://openreview.net/pdf?id=NfBrMDF0Xi)]  
[Learn more →](/inr-pinn/)


**Reduced-order models (ROMs)/Neural operators (NOs)**: Develop data-driven surrogate modeling of complex dynamics, NOs: [[AAAI 2024](https://ojs.aaai.org/index.php/AAAI/article/download/29036/29963),[ICLR 2024](https://proceedings.iclr.cc/paper_files/paper/2024/file/fe5d4bd3e2af823701b5d8f70a3c7602-Paper-Conference.pdf),[ICLR 2026](https://proceedings.iclr.cc/paper_files/paper/2026/file/c253f6fe5cc2bd1905427da63ac37917-Paper-Conference.pdf)]


## Recent News

<style>
.home-news .news-list {
  list-style: none;
  margin: 0;
  padding: 0;
}

.home-news .news-list li {
  display: grid;
  grid-template-columns: 6.5em minmax(0, 1fr);
  gap: 1em;
  margin: 0;
  padding: 0.8em 0;
  border-bottom: 1px solid rgba(128, 128, 128, 0.2);
  font-size: 0.9em;
  line-height: 1.6;
}

.home-news time {
  text-align: right;
  opacity: 0.65;
  white-space: nowrap;
  font-variant-numeric: tabular-nums;
}

.home-news .news-list li > span {
  min-width: 0;
  overflow-wrap: anywhere;
}

.home-news summary {
  width: fit-content;
  margin-top: 0.8em;
  padding: 0.4em 0;
  cursor: pointer;
  font-size: 0.85em;
}

@media (max-width: 480px) {
  .home-news .news-list li {
    grid-template-columns: 5.5em minmax(0, 1fr);
    gap: 0.65em;
  }
}
</style>

<div class="home-news" markdown="0">
  <!-- Always visible: first four news items. -->
  <ul class="news-list">
    <li>
      <time>Sep 2026</time>
      <span>One paper accepted at <b>NeurIPS 2026</b></span>
    </li>
    <li>
      <time>Sep 2026</time>
      <span>Received the KOCSEA Young Faculty Award (K-YFA) from <a href="https://www.kocseaa.org/v2/">KOCSEA</a>.</span>
    </li>
    <li>
      <time>Sep 2026</time>
      <span>One paper accepted at LoG conference 2026</span>
    </li>
    <li>
      <time>Sep 2026</time>
      <span>Congrats to Jesse and Xuanming on their Fall internships at NVIDIA and Amazon.</span>
    </li>
    <li>
      <time>Aug 2026</time>
      <span>Started a new Hoenywell-sponsored project</span>
    </li>
    <li>
      <time>Aug 2026</time>
      <span>Will be serving as an AC at <b>ICLR 2027</b></span>
    </li>
    <li>
      <time>Jun 2026</time>
      <span>Received Google TPU support!</span>
    </li>
  </ul>

  <details markdown="0">
    <summary>More news</summary>

    <!-- Move an entire li block above to feature another news item. -->
    <ul class="news-list">
      <li>
        <time>Jun 2026</time>
        <span>Congrats to Fan, Jesse, and Xuanming on their Summer internships at Siemens, Applied Materials, and Capital One.</span>
      </li>
      <li>
        <time>May 2026</time>
        <span>Fan, Jesse, and Sohyeon have advanced to doctoral candidacy. Congrats to all!</span>
      </li>
      <li>
        <time>May 2026</time>
        <span>Two papers accepted at <b>ICML 2026</b>, recognized as a gold reviewer</span>
      </li>
      <li>
        <time>Apr 2026</time>
        <span>Divesh and Ahmad successfully defended their master's theses. Congrats to all!</span>
      </li>
      <li>
        <time>Mar 2025</time>
        <span>Will be serving as an AC at <b>NeurIPS 2026</b></span>
      </li>
      <li>
        <time>Mar 2026</time>
        <span>One paper accepted by IEEE/ACM Transactions on Networking</span>
      </li>
      <li>
        <time>Feb 2026</time>
        <span>One paper accepted by Materials Today</span>
      </li>
      <li>
        <time>Feb 2026</time>
        <span>One paper accepted at <b>CVPR 2026</b></span>
      </li>
      <li>
        <time>Feb 2026</time>
        <span>One paper accepted by TMLR</span>
      </li>
      <li>
        <time>Jan 2026</time>
        <span>One paper accepted at <b>ICLR 2026</b></span>
      </li>
      <li>
        <time>Nov 2025</time>
        <span>Ray defended his master's thesis. Congrats!</span>
      </li>
      <li>
        <time>Sep 2025</time>
        <span>Will be serving as an AC at <b>ICLR 2026</b></span>
      </li>
      <li>
        <time>Sep 2025</time>
        <span>One paper accepted at <b>NeurIPS 2025</b></span>
      </li>
      <li>
        <time>Sep 2025</time>
        <span>Uvini's poster got accepted at American Vacuum Society (AVS) 71, AI/ML for Scientific Discovery session.</span>
      </li>
      <li>
        <time>Aug 2025</time>
        <span>Launching a new project with Salt River Project</span>
      </li>
      <li>
        <time>Jul 2025</time>
        <span>One paper accepted at <b>AIES 2025</b></span>
      </li>
      <li>
        <time>Jun 2025</time>
        <span>Guangting successfully defended his PhD defense.</span>
      </li>
      <li>
        <time>Apr 2025</time>
        <span>Jamie, Rushir, and John successfully defended their master's theses. Congrats to all!</span>
      </li>
      <li>
        <time>Feb 2025</time>
        <span>One paper accepted at ICLR workshop (Workshop on Neural Network Weights as a New Data Modality)</span>
      </li>
      <li>
        <time>Feb 2025</time>
        <span>One paper accepted by Results in Applied Mathematics</span>
      </li>
      <li>
        <time>Feb 2025</time>
        <span>One paper accepted by Transactions on Machine Learning Research (TMLR) <a href="https://openreview.net/pdf?id=hCxtlfvL22">[Paper]</a></span>
      </li>
      <li>
        <time>Jan 2025</time>
        <span>Three papers accebed at <b>ICLR 2025</b></span>
      </li>
      <li>
        <time>Nov 2024</time>
        <span>Launching a new project with Applied Materials Inc. <a href="https://fullcircle.asu.edu/faculty/applying-new-ai-to-microelectronics-manufacturing/">[ASU article]</a><a href="https://news.asu.edu/20250428-science-and-technology-applying-ai-microelectronics-manufacturing">[ASU article #2]</a><a href="https://news.asu.edu/20250422-science-and-technology-applied-materials-invests-asu-advance-technology-brighter-future">[ASU article #3]</a></span>
      </li>
      <li>
        <time>Nov 2024</time>
        <span>One paper accepted by Journal of Geophysical Research: Machine Learning and Computation</span>
      </li>
      <li>
        <time>Oct 2024</time>
        <span>Two papers accepted at NeurIPS workshops (Machine Learning and the Physical Sciences and Foundation Models for Science)</span>
      </li>
      <li>
        <time>Sep 2024</time>
        <span>One paper accepted by Materials Today (on the cover! <a href="/files/BFP-cover-materials-today.jpeg">Cover image</a>)</span>
      </li>
      <li>
        <time>Sep 2024</time>
        <span>One paper accepted at <b>NeurIPS 2024</b></span>
      </li>
      <li>
        <time>Sep 2024</time>
        <span>Gave a talk at DoMSS seminar in the School of Math and Stats (SoMSS) at ASU</span>
      </li>
      <li>
        <time>Jul 2024</time>
        <span>Gave a talk at MINDS seminar in Dept of Math at Postech</span>
      </li>
      <li>
        <time>Jul 2024</time>
        <span>One paper accepted at <b>CIKM 2024</b> (The first author, Fan Wu, received SIGWEB and NSF Travel Grant!)</span>
      </li>
      <li>
        <time>May 2024</time>
        <span>One paper accepted at <b>ICML 2024</b> (selected for an <a href="https://icml.cc/virtual/2024/session/35281"><span style="color:red">Oral</span> presentation</a>)</span>
      </li>
      <li>
        <time>Apr 2024</time>
        <span>Received <b> NSF CAREER award </b> <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2338909">[Award description]</a> <a href="https://fullcircle.asu.edu/faculty/new-ai-for-a-new-era-of-discovery/">[ASU article]</a></span>
      </li>
      <li>
        <time>Mar 2024</time>
        <span>One paper (Unsupervised Physics-informed Multimodal Learning) accepted by Foundations of Data Science (FoDS)</span>
      </li>
      <li>
        <time>Mar 2024</time>
        <span>One paper accepted at ICLR Workshop (Workshop on AI4DifferentialEquations in Science)</span>
      </li>
      <li>
        <time>Feb 2024</time>
        <span>Selected as one of the first teams for the inaugural <a href="https://news.asu.edu/20240118-university-news-new-collaboration-openai-charts-future-ai-higher-education">ASU AI Innovation Challenge (in collaboration with OpenAI)</a></span>
      </li>
      <li>
        <time>Jan 2024</time>
        <span>One paper accepted at <b>TheWebConf 2024</b></span>
      </li>
      <li>
        <time>Jan 2024</time>
        <span>Two papers accepted at <b>ICLR 2024</b>.</span>
      </li>
      <li>
        <time>Dec 2023</time>
        <span>One paper accepted at <b>AAAI 2024</b>.</span>
      </li>
      <li>
        <time>Dec 2023</time>
        <span>Presented two papers (one splotlight) and two workshop papers at <b>NeurIPS 2023</b>.</span>
      </li>
    </ul>
  </details>
</div>
