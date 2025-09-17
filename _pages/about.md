---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

Publications
1. Y. Liufu, L. Jin*, and S. Li, “Adaptive Noise-Learning Differential Neural Solution for Time-Dependent Equality-Constrained Quadratic Optimization”, IEEE Transactions on Neural Networks and Learning Systems, to be published, doi: 10.1109/TNNLS.2025.3561415. (中科院一区, IF=10.2, 第一作者)
2. Y. Liufu, L. Jin*, and Y. Guan, “Collaborative Physics-Informed Neural Dynamics Approach for Autonomous Vehicles With Nonconvex Safety-Critical Constraints,” IEEE Transactions on Intelligent Transportation Systems, to be published, doi: 10.1109/TITS.2025.3572336. (中科院二区, IF=7.9, 第一作者)
3. Y. Liufu, Z. Yu, and L. Jin*, “Robust Predictive Steering Control for Autonomous Vehicles With Polynomial Noise Resilience Neural Dynamics,” IEEE Transactions on Intelligent Vehicles, to be published, doi: 10.1109/TIV.2024.3507011. (中科院一区, IF=14, 第一作者)
4. Y. Liufu, L. Jin*, and S. Li, “Modified Gradient Projection Neural Network for Multiset Constrained Optimization,” IEEE Transactions on Industrial Informatics, vol. 19, no. 9, pp. 9413-9423, Sept. 2023. (中科院一区, IF=11.7, 第一作者)
5. Y. Liufu, L. Jin*, J. Xu, X. Xiao, and D. Fu, “Reformative Noise-Immune Neural Network for Equality-Constrained Optimization Applied to Image Target Detection,” IEEE Transactions on Emerging Topics in Computing, vol. 10, no. 2, pp. 973-984, Apr. 2022. (中科院二区, IF=5.1, 第一作者)
6. Y. Liufu, L. Jin* et al., “ACP-Incorporated Perturbation-Resistant Neural Dynamics Controller for Autonomous Vehicles,” IEEE Transactions on Intelligent Vehicles, vol. 9, no. 4, pp. 4675-4686, April 2024. (中科院一区, IF=14, 第一作者, ESI高被引)
7. Y. Liufu and Y. Guan, “Majorization-Minimization-Based Neural Dynamics for Time-Variant Optimization Under Multi-Set Constraints”, IEEE/CAA Journal of Automatica Sinica, to be published, 2025. (中科院一区, IF=19.2, 第一作者)
8. L. Jin*, Y. Liufu, H. Lu, and Z. Zhang, “Saturation-Allowed Neural Dynamics Applied to Perturbed Time-Dependent System of Linear Equations and Robots,” IEEE Transactions on Industrial Electronics, vol. 68, no. 10, pp. 9844-9854, Oct. 2021. (中科院一区, IF=7.5, 学生一作) 
9. M. Liu, Y. Liufu, H. Lu, and M. Shang, “Neural Solution to Dynamic Overdetermined System With Applications to Data Fitting and Parameters Estimation,” IEEE Transactions on Systems, Man, and Cybernetics: Systems, vol. 53, no. 12, pp. 7330-7341, Dec. 2023. (中科院一区, IF=8.6, 学生一作)
10. M. Liu, J. Li, Y. Liufu, W. Duan, X. Xiao, and L. Jin*, “Noise-Rejection Zeroing Dynamics for Control of Industrial Agitator Tank”, Nonlinear Dynamics, vol. 103, pp. 2581–2603, 2021. (中科院二区, IF=5.6)
11. Y. Liufu, L. Jin*, M. Liu, and S. Li, “A Recommender Algorithm: Gradient Recurrent Neural Network Applied to Yang-Baxter-Like Equation,” 2020 International Conference on Data Mining Workshops (ICDMW), Sorrento, Italy, 2020, pp. 159-165. (EI, 第一作者, 获最佳论文提名奖)
12. Y. Liufu, M. Liu, L. Jin*, and F.-Y. Wang, “Gradient Projection Differential Neural Solution for Quadratic Optimization with Quadratic Constraints: An ACP Perspective,” IEEE International Conference on Systems, Man, and Cybernetics (SMC), Hawaii, USA, 2023. (CCF C/EI, 第一作者)
13. Y. Liufu, L. Jin*, and F.-Y. Wang, “Neural-Dynamics-Based Active Steering Control for Autonomous Vehicles with Noises,” 2024 IEEE Intelligent Vehicles Symposium (IV), Jeju Island, Korea, 2024, pp. 436-441. (EI/车辆顶会, 第一作者)
14. 徐今强，刘付颖 等. 基于双目立体视觉避障的四旋翼飞行器设计[J]. 计算机测量与控制, 2020, 28(03): 183-186+191. (中文核心，学生一作)

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
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
