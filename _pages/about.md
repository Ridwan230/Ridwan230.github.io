---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- ![Illustration of learning process of AI](/images/robot2.jpg){: .align-right width="300px"} -->
I am Ridwan Mahbub, an AI enthusiast with high interest in NLP research. As an MSc student at York University, I am currently working on ethical data visualization techniques using LLMs, supervised by <a href="https://www.yorku.ca/enamulh/">Dr. Enamul Hoque</a>. My research interests lie at the intersection of NLP and Visualization. I am currently working on leveraging Large Vision-Language Models to generate animated data videos.

<!-- Research interests
======

<i class="fa-solid fa-square;" style="font-size:12px;"> </i>  HCI  <span style="width:50px;"></span>     <i class="fa-solid fa-square" style="font-size:12px;"></i>   NLP      <i class="fa-solid fa-square" style="font-size: 12px;"></i>   Dta Visualization     <i class="fa-solid fa-square" style="font-size: 12px;"></i>   Machine Learning -->


News
======

<ul class="fa-ul">
  <li>
    <span class="fa-li"><i class="fa-solid fa-star"></i></span>
    Sept 16, 2025: Our work received the <b>Best Short Paper Award</b> <i class="fa-solid fa-trophy" style="color:#d4af37;"></i> at IEEE VIS 2025. The paper explores how misleading visualizations impact vision-language models — read it <a href="https://arxiv.org/abs/2508.09716">here</a>!
  </li>
  <li>
    <span class="fa-li"><i class="fa-solid fa-star"></i></span>
    Sept 10, 2025: I am staring my internship at the <b>National Research Council Canada</b> <img src="images/nrc-logo.png" alt="NRC logo" style="height:25px; vertical-align:middle; margin-left:4px;"> 
    I’ll be working on domain-knowledge infusion into LLMs for cybersecurity tasks.
  </li>
</ul>

Publications
======

<ol>

<li>
<a href="https://arxiv.org/abs/2508.09450">From Charts to Fair Narratives: Uncovering and Mitigating Geo-Economic Biases in Chart-to-Text</a>  <br/>

<Span style="font-size:90%; "> <b>Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP) </b> </span> <br/>

This paper systematically benchmarks vision-language models on chart-to-text generation and uncovers systemic geo-economic biases, showing that models tend to favor high-income countries in their summaries even when describing the same chart.
</li>

<li>
<a href="https://arxiv.org/abs/2508.09716">The Perils of Chart Deception: How Misleading Visualizations Affect Vision-Language Models</a>  <br/>

<Span style="font-size:90%; "> <b>2025 IEEE Visualization and Visual Analytics (VIS) </b> </span> <br/>

This paper introduces the first large-scale benchmark of vision-language models on deceptive chart designs, revealing that even state-of-the-art models are vulnerable to subtle visual distortions.
</li>

<li>
<a href="https://arxiv.org/abs/2508.17398">DashboardQA: Benchmarking Multimodal Agents for Question Answering on Interactive Dashboards</a>  <br/>

<Span style="font-size:90%; "> <b>PrePrint</b> </span> <br/>

This paper introduces DashboardQA, the first benchmark for evaluating the capabilities of vision-language models in interactive dashboard navigation through question answering.
</li>

<li>
<a href="https://arxiv.org/abs/2505.08468">Judging the Judges: Can Large Vision-Language Models Fairly Evaluate Chart Comprehension and Reasoning?</a>  <br/>

<Span style="font-size:90%; "> <b>Proceedings of the 2025 Annual Meeting of the Association for Computational Linguistics (ACL), Industry Track </b> </span> <br/>

This paper presents the first comprehensive study of open-source vision-language models as automatic judges for chart comprehension and reasoning, highlighting their potential as cost-effective evaluators while also exposing persistent biases.
</li>

<li>
<a href="https://aclanthology.org/2023.emnlp-main.920/">Unveiling the Essence of Poetry: Introducing a Comprehensive Dataset and Benchmark for Poem Summarization</a>  <br/>

<Span style="font-size:90%; "> <b>Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing (EMNLP) </b> </span> <br/>

This work benchmarks the creative language understanding and summarizing capacity of language models
and highlights numerous short-comings of prevalent text summarization models.
</li>

<li>
<a href="https://ieeexplore.ieee.org/abstract/document/10056104">A Comparative Analysis of Efficient Convolutional Neural Network Based Methods for Plant Disease Classification</a> <br/>

<span style="font-size:90%; "> <b>2022 25th International Conference on Computer and Information Technology (ICCIT) </b> </span> <br/>
The work delves into the complexities of plant disease classification, covering aspects such as available
datasets, transfer learning, and a comparative analysis of lightweight CNN models for leaf disease.
</li>

</ol>


<!-- Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header.

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons.

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
