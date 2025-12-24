---
permalink: /
title: "Abote Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an **Associate Professor** *(pending formal appointment)* at the **School of Computer Science and Artificial Intelligence**, **Zhengzhou University (ZZU)**. I will receive my **Ph.D. degree in Software Engineering** from **Zhengzhou University** in **2026**, supervised by *Academic Guoliang Chen* and *Prof. Yafei Li*.  
In 2024, I was supported by the **China Association for Science and Technology Young Talent Support Program for Doctoral Students (*Qingtuo*)**. I have published **more than 10 research papers** in international journals/conferences, including *IEEE TKDE*, *IEEE TMC*, *IEEE TITS*, *IEEE ICDE*, *PVLDB*, *IJCAI*, and *ACM CIKM*.  
I also serve as a **regular reviewer** for journals such as *IEEE TKDE* and *IEEE TMC*, and conferences including *ICDE*, *SIGKDD*, *IJCAI*, and *AAAI*.

## **Research Interests**

My research interests cover **Spatio-temporal Data Management and Analytics** and **Artificial Intelligence**, with a particular focus on:
- **Spatial Crowdsourcing**  
  *Spatio-temporal task modeling, large-scale optimization, and data-driven urban service systems.*
- **Human-in-the-Loop**  
  *Collaborative human–AI decision-making for complex spatio-temporal tasks, sim-to-real transfer, and robust learning under uncertainty.*
- **Intelligent Systems**  
  *Large language models, multi-agent systems, and intelligent unmanned systems.*

## **Publications**

( *: equal contribution, #: corresponding author.)

- <span style="color:blue;"><strong>[ICDE'26]</strong></span> High-Fidelity Task Assignment in Spatial Crowdsourcing via Implicit Human Feedback.  
  **Qingshun Wu**, Yafei Li, Jinxing Yan, Yuanyuan Jin, Hua Wang, Mingliang Xu.  
  *IEEE International Conference on Data Engineering*, 2026.  
  <span style="color:red;"><strong>(CCF-A)</strong></span>

- <span style="color:blue;"><strong>[IJCAI'25]</strong></span> HLMTrans: A Sim-to-Real Transfer Framework for Spatial Crowdsourcing with Human-Guided Language Models.  
  **Qingshun Wu**, Yafei Li, Lulu Li, Yuanyuan Jin, Shuo He, Mingliang Xu.  
  *International Joint Conference on Artificial Intelligence*, 2025.  
  <span style="color:red;"><strong>(CCF-A)</strong></span>

- <span style="color:blue;"><strong>[TMC'25]</strong></span> Adaptive Task Assignment in Spatial Crowdsourcing: A Human-in-the-Loop Approach.  
  **Qingshun Wu**, Yafei Li, Jinxing Yan, Mei Zhang, Jianliang Xu, Mingling Xu.  
  *IEEE Transactions on Mobile Computing*, 2025.  
  <span style="color:red;"><strong>(CCF-A)</strong></span>

- <span style="color:blue;"><strong>[TMC'24]</strong></span> Prediction-Aware Adaptive Task Assignment for Spatial Crowdsourcing.  
  **Qingshun Wu**, Yafei Li, Guanglei Zhu, Baolong Mei, Jianliang Xu, Mingling Xu.  
  *IEEE Transactions on Mobile Computing*, 2024.  
  <span style="color:red;"><strong>(CCF-A)</strong></span>

- <span style="color:blue;"><strong>[TKDE'23]</strong></span> Efficient Adaptive Matching for Real-Time City Express Delivery.  
  Yafei Li, **Qingshun Wu**, Xin Huang, Jianliang Xu, Wanru Gao, Mingliang Xu.  
  *IEEE Transactions on Knowledge and Data Engineering*, 2023.  
  <span style="color:red;"><strong>(CCF-A)</strong></span>

- <span style="color:blue;"><strong>[PVLDB'22]</strong></span> AMRAS: A Visual Analysis System for Spatial Crowdsourcing.  
  **Qingshun Wu**, Yafei Li, Huiling Li, Di Zhang, Guanglei Zhu.  
  *Proceedings of the VLDB Endowment*, 2022.  
  <span style="color:red;"><strong>(CCF-A)</strong></span>

- <span style="color:blue;"><strong>[CIKM'22]</strong></span> PRID: An Efficient Pub/Sub Ride Hitching System.  
  Yafei Li, Lei Gao, Haobo Sun, Huiling Li, **Qingshun Wu***.  
  *ACM International Conference on Information and Knowledge Management*, 2022.  
  <span style="color:red;"><strong>(CCF-B)</strong></span>





A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
