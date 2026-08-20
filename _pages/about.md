---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final-year Ph.D. student at Purdue University in the Davidson School of Chemical Engineering ([Li Group](https://canli1.github.io)).

I received M.Phil. from the Department of Chemical Engineering and Biotechnology at University of Cambridge (2021), and B.Eng. from the Department of Chemical and Environmental Engineering at University of Nottingham (2020). 

**I am actively seeking full-time job opportunities and research collaborations**.

<!-- # Research interests -->
My research interests lie broadly at the interface between machine learning and optimization, with a focus on accelerating hard decision-making problems, improving explainability of optimization models, and preserving feasibility in deep learning models. Current work follows three connected directions.

## Learning to Optimize
Many industrial decision-making problems can be formulated as combinatorial optimization problems, yet solving them to global optimality remains computationally challenging. My research develops learning-based approaches to accelerate the branch-and-bound methods without sacrificing correctness guarantees.

**Related publication:** [Solving Max-Cut to Global Optimality via Feasibility-Preserving Graph Neural Networks](https://arxiv.org/abs/2605.07113)

## LLMs for Optimization
Optimization models are often developed by experts but used by domain practitioners who need to understand formulations, diagnose infeasibility, and evaluate possible model changes. This direction proposes LLM-based systems that connect optimization models, solvers, and users through natural language. 

**Related publications:** [OptiChat: Bridging Optimization Models and Practitioners with Large Language Models](https://pubsonline.informs.org/doi/abs/10.1287/ijds.2025.0074); [Diagnosing Infeasible Optimization Problems Using Large Language Models](https://www.tandfonline.com/doi/abs/10.1080/03155986.2024.2385189)

## Deep Learning Models with Hard Constraints
Deep learning models are widely used in science and engineering as surrogates, but their predictions may violate physical laws, domain knowledge and operational requirements. This work explores neural architectures to enforce input-dependent hard constraints with minimal computational overhead. 

**Related publications:** [Enforcing Hard Linear Constraints in Deep Learning Models with Decision Rules](https://arxiv.org/html/2505.13858v1); [Physics-informed neural networks with hard linear equality constraints](https://www.sciencedirect.com/science/article/abs/pii/S0098135424001820)



<!-- Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png) -->
