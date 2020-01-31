---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a theoretical physicist interested in plasmas physics, particularly with an astrophysical spin. Currently, I am a final year graduate student under the supervision of Prof. Dr. Per Helander at the Max-Planck-Institue for Plasma Physics. 



Research Interests
------

My research interests include general plasma physics, plasma astrophysics and astrophysical gas dynamics. 

My current work as a theoretical physicist focuses on the kinetic theory of electron-positron plasmas. During my PhD project, I have been responsible for a number of subprojects, which has allowed me to investigate areas of plasma physics such as the stability and equilibria of non-neutral plasmas. I am currently working on the effects of cyclotron-cooling, anisotropy and collisions in models of electron-positron plasmas, investigating how this can impede or enhance the stability of laboratory borne pair  plasmas. I am keen to expand on my PhD work along an astrophysical axis and I am particularly interested in the behaviour of electron-positron plasmas in pulsar magnetospheres.

I have directed my research to enable me to utilise both analytic calculations and numerical simulations. With a solid grounding in both methods, I have a strong preference for the former. However, I have found the incorporation of numerical simulations and calculations in my work extremely valuable and a large part of my PhD work has been centred around gyrokinetic simulations of electron-positron plasmas in closed field-line geometry. I believe learning new techniques and trying new ideas is a central part of furthering and improving my research and I have experience using both Eulerian and Particle-In-Cell codes.

Example: adding an image

![Linear stability](/images/figtry.png)

Biography
------

Previous to my doctoral training, I read for a bachelor’s degree in Mathematics, followed by a masters degree in Mathematical and Theoretical Physics at [Merton College](https://www.merton.ox.ac.uk/), University of Oxford. I graduate with distinction from the MMathPhys program in the summer of 2017.

As an undergraduate in mathematics, I applied myself to large variety of courses, ranging from Rings and Modules to Applied Partial Differential Equations, Electromagnetism, Viscous Flow and Numerical Solutions to Differential Equations. As part of the MMathPhys program I specialised in plasma physics and astrophysical gas dynamics, taking numerous courses in these areas. In addition to the advanced plasma physics courses I took in my final year.

I studied Astrophysical Gas Dynamics under Prof. Steven Balbus, which culminated in a dissertation on “The Goldreich-Schubert-Fricke instability in the presence of background magnetic fields.” Here, I expanded my learning beyond the parameters of the university mathematics course, allowing me to delve into exciting areas in astrophysical fluid dynamics, magnetohydrodynamics and plasma physics. This experience bolstered my interest in pursuing further study in these areas.

During my time at Oxford, I received a number of prizes for my academic writing and excellent performance in University examinations. On several occasions I have also secured competitive funding and grant money to undertake summer research placements and travel to conferences.

![alt-text-1](/images/new1.png "title-1") ![alt-text-2](/images/new2.png "title-2") ![alt-text-2](/images/new3.png "title-2")


Previous Research Experience 
------


I have been chosen to undertake several paid positions in various groups of the Mathematics and Physics departments at the University of Oxford. In total, I have been selected for four research internships, each of which has led to publications and long lasting collaborations. One such position was a research project in the Oxford department of Atmospheric, Oceanic and Planetary Physics, which focused on atmospheric dynamics (specifically high pressure blocking systems). Here, I gained extensive research experience, which has been invaluable to my subsequent work. The project work emphasised computation, requiring me to write numerous computer programs. This allowed me to use my knowledge of statistics to analyse large data sets, for example, writing Monte-Carlo simulations to preform statistical significance tests. I was also required to use my knowledge of fluid mechanics and atmospheric dynamics to attempt to describe and explain the results of the numerical computations, backing these predictions up with more data analysis. I expanded and consolidated my knowledge by attending numerous seminars and colloquia on astrophysical and geophysical fluid dynamics throughout these projects, as well as engaging in many stimulating conversations with leading academics in other fields.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).


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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
