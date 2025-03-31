---
permalink: /
title: "Mile-Group is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](<url id="cvl1ejqn754bath1rfc0" type="url" status="parsed" title="GitHub - academicpages/academicpages.github.io: Github Pages template based upon HTML and Markdown for personal, portfolio-based websites." wc="5466">https://github.com/academicpages/academicpages.github.io</url> ) and hosted on GitHub pages. [GitHub pages](<url id="cvl1ejqn754bath1rfb0" type="url" status="parsed" title="GitHub Pages" wc="4593">https://pages.github.com</url> ) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](<url id="cvl1ejqn754bath1rfbg" type="url" status="parsed" title="Minimal Mistakes" wc="866">https://mmistakes.github.io/minimal-mistakes/</url> ) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this template](<url id="cvl1ejqn754bath1rfc0" type="url" status="parsed" title="GitHub - academicpages/academicpages.github.io: Github Pages template based upon HTML and Markdown for personal, portfolio-based websites." wc="5466">https://github.com/academicpages/academicpages.github.io</url> ) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](<url id="cvl1ejqn754bath1rfcg" type="url" status="parsed" title="GitHub Pages" wc="4593">https://pages.github.com/</url> ) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](<url id="cvl1ejqn754bath1rfd0" type="url" status="failed" title="" wc="0">https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb</url> ) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](<url id="cvl1ejqn754bath1rfig" type="url" status="failed" title="" wc="0">https://academicpages.github.io/talkmap.html</url> ).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required! )
1. Fork [this template](<url id="cvl1ejqn754bath1rfc0" type="url" status="parsed" title="GitHub - academicpages/academicpages.github.io: Github Pages template based upon HTML and Markdown for personal, portfolio-based websites." wc="5466">https://github.com/academicpages/academicpages.github.io</url> ) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](<url id="cvl1ejqn754bath1rfeg" type="url" status="failed" title="" wc="0">http://archive.is/3TPas</url> ) showing what files were changed to set up [an example site](<url id="cvl1ejqn754bath1rff0" type="url" status="failed" title="" wc="0">https://getorg-testacct.github.io</url> ) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](<url id="cvl1ejqn754bath1rffg" type="url" status="failed" title="" wc="0">https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml</url> ), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](<url id="cvl1ejqn754bath1rfg0" type="url" status="failed" title="" wc="0">https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml</url> ). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](<url id="cvl1ejqn754bath1rfgg" type="url" status="failed" title="" wc="0">https://github.com/academicpages/academicpages.github.io/tree/master/_talks</url> ). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](<url id="cvl1ejqn754bath1rfh0" type="url" status="failed" title="" wc="0">https://academicpages.github.io/talks</url> ), each [individual page](<url id="cvl1ejqn754bath1rfhg" type="url" status="failed" title="" wc="0">https://academicpages.github.io/talks/2012-03-01-talk-1</url> ) for specific talks, the talks section for the [CV page](<url id="cvl1ejqn754bath1rfi0" type="url" status="failed" title="" wc="0">https://academicpages.github.io/cv</url> ), and the [map of places you've given a talk](<url id="cvl1ejqn754bath1rfig" type="url" status="failed" title="" wc="0">https://academicpages.github.io/talkmap.html</url> ) (if you run this [python file](<url id="cvl1ejqn754bath1rfj0" type="url" status="failed" title="" wc="0">https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py</url> ) or [Jupyter notebook](<url id="cvl1ejqn754bath1rfd0" type="url" status="failed" title="" wc="0">https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb</url> ), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](<url id="cvl1ejqn754bath1rfk0" type="url" status="failed" title="" wc="0">https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator</url> 
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](<url id="cvl1ejqn754bath1rfkg" type="url" status="failed" title="" wc="0">https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md</url> ) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](<url id="cvl1ejqn754bath1rfl0" type="url" status="failed" title="" wc="0">https://academicpages.github.io/markdown/</url> ), the [growing wiki](<url id="cvl1ejqn754bath1rflg" type="url" status="failed" title="" wc="0">https://github.com/academicpages/academicpages.github.io/wiki</url> ), and you can always [ask a question on GitHub](<url id="cvl1ejqn754bath1rfm0" type="url" status="failed" title="" wc="0">https://github.com/academicpages/academicpages.github.io/discussions</url> ). The [guides for the Minimal Mistakes theme](<url id="cvl1ejqn754bath1rfmg" type="url" status="failed" title="" wc="0">https://mmistakes.github.io/minimal-mistakes/docs/configuration/</url> ) (which this theme was forked from) might also be helpful.

Our Research Interests
------
Mile-Group is dedicated to exploring the cutting-edge field of intelligent robotics. Our research focuses on developing advanced algorithms and systems that enable robots to perceive, reason, and interact with complex environments. We are particularly interested in the following areas:

- **Autonomous Navigation**: Designing efficient and robust navigation systems that allow robots to move autonomously in dynamic and unstructured environments.
- **Machine Learning for Robotics**: Applying and advancing machine learning techniques to enhance robot learning capabilities, including reinforcement learning, deep learning, and transfer learning.
- **Human-Robot Interaction**: Creating intuitive and effective interaction methods between humans and robots, aiming to improve collaboration and communication.
- **Robot Vision**: Developing computer vision algorithms that enable robots to interpret visual data accurately, supporting tasks like object recognition and scene understanding.
- **Robotic Manipulation**: Investigating advanced manipulation techniques that allow robots to perform complex tasks with precision and adaptability.

We believe that intelligent robotics has the potential to revolutionize various industries and improve human life. Our goal is to push the boundaries of what robots can achieve and contribute to the advancement of this exciting field.
