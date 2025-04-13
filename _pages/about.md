---
permalink: /
title: "Introduction"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Zhaoju Yang (杨兆举). Currently, I am a tenure-track research professor at the [School of Physics](https://physics.zju.edu.cn/), [Zhejiang University](https://www.zju.edu.cn/) at Hangzhou city, China.

Research Interest
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Selected publications
======
1. Q. Liang#, Z. Dong#,J.-S. Pan#, H. Wang, H. Li, Z. Yang*, W. Yi* &B. Yan*. Chiral dynamics of ultracold atoms under a tunable SU(2) synthetic gauge field. Nature Physics 20,1738 (2024). 
1. Y. Sun#, X. Hou#, T. Wan, F. Wang, S. Zhu, Z. Ruan*, Z. Yang*. Photonic Floquet skin-topological effect. Phys. Rev. Lett. 132, 063804 (2024). ESI highly cited paper.
1. Z. Dong#, H. Li#, T. Wan#, Q. Liang, Z. Yang*, B. Yan*. Quantum time reflection and refraction of ultracold atoms. Nature Photonics 18, 68-73 (2024). ESI highly cited paper.
1. H. Zhang#, Y. Sun#, J. Huang#, B. Wu, Z. Yang*, K. Y. Bliokh, Z. Ruan*. Topologically crafted spatiotemporal vortices in acoustics. Nature Communications 14, 6238 (2023).
1. T. Biesenthal, L. Maczewsky, Z. Yang*, M. Kremer, M. Segev, A. Szameit*, M. Heinrich*. Fractal photonic topological insulator. Science 376, 1114-1119 (2022). Physics World. ESI highly cited paper.
1. Z. Yang, E. Lustig, Y. Lumer and M. Segev*. Photonic Floquet topological insulators in a fractal lattice. Light: Science & Applications 9, 128 (2020).
1. Z. Yang, E. Lustig, Y. Lumer and M. Segev*. Photonic Floquet topological insulators in a fractal lattice. Light: Science & Applications 9, 128 (2020).
1. Z. Yang#, E. Lustig#, G. Harari, Y. Plotnik, Y. Lumer, M. Bandres, and M. Segev*. Mode-locked topological insulator laser utilizing synthetic dimensions. Phys. Rev. X 10, 011059 (2020).
1. F. Gao#, H. Xue#, Z. Yang*, K. Lai, Y. Yu, X. Lin, Y. Chong, G. Shvets*, B. Zhang*. Topologically-protected refraction of robust kink states in valley photonic crystals. Nature Physics 14, 140-144 (2018). ESI highly cited paper.
Z. Yang, F. Gao, Y. Yang, and B. Zhang*. Strain-induced gauge field and Landau levels in acoustic structures. Phys. Rev. Lett. 118, 194301 (2017).
Z. Yang, B. Zhang*. Acoustic type-II Weyl nodes from stacking dimerized chains. Phys. Rev. Lett. 117, 224301 (2016).
Z. Yang, F. Gao, X. Shi, X. Lin, Z. Gao, Y. Chong, and B. Zhang*. Topological acoustics. Phys. Rev. Lett. 114, 114301 (2015). PRL Editors' suggestion and Featured in physics. ESI highly cited paper.








<!-- 
Research Interest
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Site-wide configuration
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
-->
<!-- 这是注释内容，不会在渲染后的页面显示 
For more info
------m
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
-->
