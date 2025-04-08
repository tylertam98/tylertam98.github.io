---
permalink: /
title: "Academic Page"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<div style="text-align: justify;">
Dr. Tan Qichen is an Associate Professor at Soochow University. He earned his BEng in Software Engineering from the <strong>University of Electronic Science and Technology of China (UESTC)</strong> in 2020 and completed his PhD in Intelligent Transportation at the <strong>Hong Kong University of Science and Technology (HKUST)</strong> in 2024. Prior to joining Soochow University, he continued his research as a post-doctoral fellow at HKUST, deepening his expertise in low-altitude economy and intelligent technologies. Dr. Tan’s research focuses on solving complex challenges at the intersection of technology and sustainability. His work centers on intelligent path planning for low-altitude aircraft, acoustic simulation of aircraft, multimodal data fusion, noise visualization, and embodied artificial intelligence. His innovative approaches aim to create smarter, quieter, and more efficient urban environments. <strong>Dr. Tan warmly invites passionate undergraduate and master’s students to join our vibrant research team. Here, you’ll embark on a transformative journey to expand your global perspective, engage in pioneering scientific exploration, and foster interdisciplinary innovation.</strong>
</div>

Selected Publications
======
Major Research Programs
------
[1] Tan, Q., Hou, J., Li, Y., Qu, R., Zhou, P., Zhong, S., ... & Zhang, X. (2024). Exploring noise reduction strategies: Optimizing drone station placement for last-mile delivery. Transportation Research Part D: Transport and Environment, 133, 104306. [Link](https://www.sciencedirect.com/science/article/pii/S1361920924002633)

[2] Tan, Q., Li, Y., Wu, H., Zhou, P., Lo, H. K., Zhong, S., & Zhang, X. (2024). Enhancing sustainable urban air transportation: Low-noise UAS flight planning using noise assessment simulator. Aerospace Science and Technology, 147, 109071. [Link](https://www.sciencedirect.com/science/article/pii/S1270963824002049)

[3] Tan, Q., Zhong, S., Qu, R., Li, Y., Zhou, P., Lo, H. K., & Zhang, X. (2024). Low-noise flight path planning of drones based on a virtual flight noise simulator: A vehicle routing problem. IEEE Intelligent Transportation Systems Magazine. [Link](https://ieeexplore.ieee.org/abstract/document/10540653)

[4] Tan, Q., Bian, H., Guo, J., Zhou, P., Lo, H. K., Zhong, S., & Zhang, X. (2023). Virtual flight simulation of delivery drone noise in the urban residential community. Transportation Research Part D: Transport and Environment, 118, 103686. [Link](https://www.sciencedirect.com/science/article/pii/S1361920923000834)

[5] Tan, Q., Li, Y., Bao, H., Zhou, P., Lo, H. K., Zhong, S., & Zhang, X. (2024). Low-Noise Multi-Agent Intelligent Navigation for Unmanned Aircraft Systems. In 30th AIAA/CEAS Aeroacoustics Conference (2024) (p. 3234). [Link](https://arc.aiaa.org/doi/abs/10.2514/6.2024-3234)

Collaborative Research Programs
------
[1] Hou, J., Tan, Q., Wang, Z., Mok, K. P., Zhou, P., & Zhang, X. (2025). Inshore sailing route optimization integrating terrain-influenced wind field. Ocean Engineering, 326, 120848. 

[2] Bao, H., Tan, Q., Zhou, P., Chen, W., Zhang, X., & Zhong, S. (2025, February). On the Gaussian beam tracing method for long-distance sound wave propagation in non-uniform mean flows. In Proceedings A (Vol. 481, No. 2307, p. 20240485). The Royal Society.

[3] Bian, H., Tan, Q., Zhong, S., & Zhang, X. (2022). Efficient computation of broadband noise propagation using Gaussian beam tracing method. The Journal of the Acoustical Society of America, 151(5), 3387-3397.

[4] Bian, H., Tan, Q., Zhong, S., & Zhang, X. (2021). Assessment of UAM and drone noise impact on the environment based on virtual flights. Aerospace Science and Technology, 118, 106996.

[5] Hou, J., Liu, G., Tan, Q., Mok, K. P., Song, W., Chan, K. Y., ... & Zhang, X. (2024). Velocity prediction program for windsurfing: A hierarchical approach integrating biomechanical insights. Ocean Engineering, 312, 119070.

Award
======
Postgraduate Studentship (PGS), HKUST, 2020
Excellent Graduate Student, UESTC, 2020
Excellent Student Scholarship, UESTC, 2016-2019

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

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
