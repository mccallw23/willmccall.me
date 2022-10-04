---
layout: home
header:
  title: Will McCall
  icons:
    - title: Email
      icon: fa-envelope
      type: fa
      site_data: email
    - title: GitHub
      icon: fa-github
      type: fab
      site_data: github
    - title: LinkedIn
      icon: fa-linkedin-in
      type: fab
      site_data: linkedin
    - title: Resume
      icon: fa-file-alt
      type: fa
      site_data: cv_path

sections:
  - type: chat.html
    section_id: chat
    title: Chat with my hiring advocate!
    background_style: bg-secondary
  - type: multipane.html
    section_id: about
    background_style: bg-secondary
    title: About me
    panes:
      - type: bio-timeline.html
        title: Bio
        before_text: As a junior at [Dartmouth College](https://home.dartmouth.edu/){:target="_blank"}, majoring in Computer Science and minoring in Human Centered Design, I am currently a Research Assistant in the [Contextual Dynamics Lab](https://context-lab.com/){:target="_blank"} and a TA for the [Dartmouth CS Department](https://web.cs.dartmouth.edu/){:target="_blank"}.
        bio_paragraphs:
          - text: I have always had a curious, creative, and entrepreneurial spirit and a passion for technology. Growing up, I developed an interest in STEAM while volunteering as a 3D printer coach in the Westport Library MakerSpace.
            image: assets/img/bio/me.png
          - text: These interests led me to pursue a degree in Computer Science at Dartmouth College, where I joined the Entrepreneurship Living Community, and began working for the [Dartmouth Computer Science Department](https://web.cs.dartmouth.edu/){:target="_blank"} as a TA, helping college and graduate students learn Object Oriented Programming, Data Structures, and Web Development.  Using concepts from these classes, I implemented a prediction market trading bot, which identifies arbitrage opportunities in multi contract prediction markets with low liquidity, and is available on [GitHub](https://github.com/mccallw23/PredictBot){:target="_blank"}.
            image: assets/img/bio/dartmouth.png
          - text: I then joined the [Contextual Dynamics Lab](https://www.context-lab.com/){:target="_blank"}
             (PI&#58; [Dr. Jeremy Manning](https://pbs.dartmouth.edu/people/jeremy-rothman-manning){:target="_blank"})
             as a Presidential Research Scholar studying parallels between neural activity and stock market dynamics.
             Working with NumPy and Pandas, I helped create a PCA model for dimensionality reduction on stock market data and subsequently analyze
             the predictive value of high order price correlations, with the end goal of building a trading AI.  
            image: assets/img/bio/cdl-logo.png
          - text: This fall, I joined [Canopy](https://www.heycanopy.com/){:target="_blank"}, As a Software engineering intern for the fall, where I helped to improve the User Interface Design through designing an implementing changes to the code base.  My other interests include Financial Technology, Full Stack Development, Machine Learning, 3D printing, Virtual Reality, and UI/UX design, and am currently looking to apply myself in one of these disciplines in an Internship for the Summer of 2022.
            image: assets/img/bio/WillClass.png
        timeline:
          start: 2018
          end: 2022
          events:
          - title: Senior Class President, Green's Farm's Academy
            start: 2018.25
            end: 2019.75
            color: 083D77
          - title: Varsity Soccer Captain, Green's Farm's Academy
            start: 2018.5
            end: 2018.75
            color: 38302E
          - title: Varsity T&F Captain, Green's Farm's Academy
            start: 2019.25
            end: 2019.5
            color: 38302Eh
          - title: Undergraduate CS/Math Major, Dartmouth College
            start: 2019.75
            end: 2022
            color: 00693E
          - title: Private Tutor, Intro to Computer Science
            start: 2020
            end: 2020.25
            color: B7A196
          - title: Founded/Operated WeTutorCT.com
            start: 2020.5
            end: 2021
            color: B7A196
          - title: Teaching Assistant, Object Oriented Programming @ Dartmouth
            start: 2021
            end: 2022
            color: EDD4B2
          - title: Presidential Scholar, Contextual Dynamics Lab
            start: 2021.5
            end: 2022
            color: EDD4B2
          - title: Teaching Assistant, Web Development @ Tuck Business School
            start: 2021.75
            end: 2022
            color: EDD4B2
          - title: Lead Tutor, Varsity Tutors
            start: 2020.5
            end: 2021.5
            color: B7A196

      - type: skills.html
        title: Skills
        categories:
          - title: Programming & web development
            skills:
              - image: assets/img/skills/Java.png
                caption: Java
              - image: assets/img/skills/python.png
                caption: Python
              - image: assets/img/skills/javascript.png
                caption: JavaScript
              - image: assets/img/skills/html.png
                caption: HTML
              - image: assets/img/skills/css.png
                caption: CSS
              - image: assets/img/skills/shell.png
                caption: Shell
              - image: assets/img/skills/latex.png
                caption: TeX/LaTeX
              - image: assets/img/skills/jekyll.png
                caption: Jekyll
          - title: Development tools
            skills:
              - image: assets/img/skills/git.png
                caption: Git/GitHub
              - image: assets/img/skills/conda.png
                caption: Conda
              - image: assets/img/skills/jupyter.png
                caption: Jupyter/IPython/ Colaboratory
              - image: assets/img/skills/packaging.png
                caption: Python packaging
          - title: Data analysis & visualization
            skills:
              - image: assets/img/skills/scipy.png
                caption: SciPy
              - image: assets/img/skills/numpy.png
                caption: NumPy
              - image: assets/img/skills/pandas.png
                caption: Pandas
              - image: assets/img/skills/matplotlib.png
                caption: Matplotlib
          - title: Non-technical
            skills:
              - image: assets/img/skills/maya.png
                caption: Maya
              - image: assets/img/skills/spanish.png
                caption: Spanish
              - image: assets/img/skills/writing.png
                caption: Writing
              - image: assets/img/skills/speaking.png
                caption: Public speaking
              - image: assets/img/skills/leadership.png
                caption: Organizational leadership

  - type: multipane.html
    section_id: software
    background_style: bg-primary
    title: Software
    before_text: I also develop and maintain software on Github in addition to contributing to open source projects.  
    after_text: ... and also
     [this website](https://github.com/mccallw23/willmccall.me){:target="_blank"}!
    panes:
      - type: software.html
        title: "My Software"
        items:
          - title: PredictBot
            role: Inventor, Developer
            description: PredictBot is a personal project that Identifies arbitrage opportunities in the Political
             prediction market `PredictIt`. Using negative risk, it identifies opportunities to hedge against all
             possible market outcomes, and thus guarentee a profit. `FullMarketAccess` is a Java class which parses the PredictIt Market API for price information, loading it into internal `Market` objects which are composed of `Contract` objects.  It then runs a series of simple tests to determine if a Market can be arbitraged. For more on how it works, see the github repo `README` file.  Currently, the most practical way to find arbitrage on Predictit is to examine the sum of "no" prices in large contract markets. In a given market in which one outcome must happen, the sum of all "yes" should add to 100%, implying that sum of all "no" should be (n-1) *(100%) where n is the number of contracts in the market. By calculating this value for all Markets, PredictBot identifies when the true sum of "no" prices are less than (n-1) * (100), and returns the market to the user if it is. As an example, If (n-1)*100 = 400, and the true market value is 3.96, this presents an opportunity to buy $4 for the price of $3.96.
            icons:
              - icon: fa-github-square
                type: fab
                text: View on GitHub
                url: https://github.com/mccallw23/PredictBot
          - title: Tiny Search Engine
            role: Developer
            description: The Tiny Search Engine Crawls and Indexes webpages, and handles user Queries for relevant information. It was designed and implemented in C with a special emphasis on modularity. The **crawler** crawls a website and retrieves webpages starting with a specified URL. It parses the initial webpage, extracts any embedded URLs and retrieves those pages, and crawls the pages found at those URLs, but limits itself to `maxDepth` hops from the seed URL and to URLs that are 'internal' to the designated CS50 server. When the crawler process is complete, the indexing of the collected documents can begin.  The index module is designed to take as input a page directory and index file name in the format `./index pagedirectory indexfilename` This module then outputs the data to indexfilename where each line of the file contains data about word frequency in the form `word docID count [docID count]...`. querier.c is activated by the command ./querier directory indexfile after it is made using `make`. It is designed to execute from a command line with usage syntax `./querier pageDirectory indexFilename` where `pageDirectory` is the pathname of a directory produced by the Crawler, and *where `indexFilename` is the pathname of a file produced by the Indexer.
            icons:
              - icon: fa-github-square
                type: fab
                text: View on GitHub
                url: https://github.com/mccallw23/TinySearchEngine
          - title: Sudoku Solver
            role: Developer
            description: Sudoku is well known logic puzzle where numbers between 1 and 9 are placed on a 9x9 grid of cells. This module is capable of randomly generating and returning a sudoku board with just 1 unique solution to be solved.  It is also capable of completely solving a given 9x9 sudoku board if a solution exists.  To build this module run command `make`.  For representative test cases, run `make test`.  To make a new random sudoku puzzle, run `./creator [filename]` which writes a randomly generated and formatted sudoku puzzle to output file [filename].  To solve a given sudoku puzzle, run `./solver [fileinput] [fileoutput]`.
            icons:
              - icon: fa-github-square
                type: fab
                text: View on GitHub
                url: https://github.com/ContextLab/lab-manual
      - type: software.html
        title: Software I contribute to
        items:
          - title: stockprophet
            role: Developer, Researcher
            description: The goal of StockProphet is to understand the complex dynamics of interaction in financial markets.  This undertaking comprises four major projects; Data curation, feature generation, trading strategies, and backtesting.
            icons:
              - icon: fa-github-square
                type: fab
                text: View on GitHub
                url: https://github.com/mccallw23/stockprophet
          - title: Contexual Dynamics Lab Manual.
            role: maintainer
            description: lab manual and source code for the
             [Contextual Dynamics Lab](http://www.context-lab.com/){:target="_blank"} (PI&#58;
             [Jeremy Mannning](https://pbs.dartmouth.edu/people/jeremy-rothman-manning){:target="_blank"}). A publicly
             Shared GitHub repo designed to help onboard

              In addition
             to lab policies and practices, it contains useful guides for tools and techniques frequently used in the
             CDL, as well as serves as the lab's on-boarding platform for new members. We've chosen to share it
             publicly in the hopes that others may find its format, content, or philosophy useful, or offer us
             feedback on how to improve.
            icons:
              - icon: fa-github-square
                type: fab
                text: View on GitHub
                url: https://github.com/contextlab/lab-manual
              - icon: fa-file-pdf
                type: fas
                text: Download PDF
                url: https://github.com/ContextLab/lab-manual/raw/master/lab_manual.pdf

  - type: multipane-filter.html
    section_id: Projects
    background_style: bg-secondary
    title: Projects
    pane_type: publication-cards.html
    before_text: >+
     In addtion to writing code, I love to create projects related to 3D modelling, UI/UX, and Math education. Here are some examples of my work:
    panes:
      - title: CAD
        filter: mod
      - title: Misc
        filter: misc
    items:
      - type: mod
        title: The Beautiful checkerboard tiling problem.
        text: Designed as a gentle introduction to Induction for Discreet Math students, this project and helped me solidify animation skills, while deepening my understanding of Discreet Math. This project was selected as a finalist in the first-ever 3Blue1Brown Summer of Math exposition Competition. It was selected from over 1500 entries, and received personal recognition from Grant Sanderson. It was designed and animated in Maya.
        image: assets/img/projects/chessboard.png
        pdf_url: https://www.youtube.com/watch?v=GlQCTOG5HqA&ab_channel=WillMcCall
      - type: mod
        title: Remote Control Haptic Feedback Glove
        text: Implemented using C++, this project aimed to give the user the ability to remotely control a robotic hand and gather haptic data about the object being interacted with. This project has potential applications in Virtual Reality, missions to other Planets, and rescue operations in dangerous areas for human beings.
        image: assets/img/projects/haptic.png
        pdf_url: https://www.youtube.com/watch?v=oybqzQ8VqGU&ab_channel=WillMcCall
      - type: mod
        title: Conic Sections and 4D parametrics
        text: Conic Sections are at the heart of a surprising number of everyday phenomena, ranging from Newtonian Motion to 4D parametrics. In this project, I took inspiration from the book Flatland to create a simulated world full of cones, and used them to explain a number of interesting mathematical facts all tied together through the lense of better understanding the cone. modelled in Sketchup.
        image: assets/img/projects/conics.png
        pdf_url: https://www.youtube.com/watch?v=hbYty7GuQg8&ab_channel=WillMcCall
      - type: mod
        title: Camera Rocket Projectiles
        text: Designed custom camera housing to launch cameras out of a potato cannon.
        image: assets/img/projects/dart.png
        pdf_url: https://www.youtube.com/watch?v=tEWj1DHAKsc&ab_channel=WillMcCall
      - type: mod
        title: Animation and 3D modelling portfolio
        text: Rendering and Animations done in Maya.
        image: assets/img/projects/anim.png
        pdf_url: https://www.youtube.com/watch?v=YuTxAVSubKo&ab_channel=WillMcCall
      - type: misc
        title: UI/UX prototype
        text: Designed a User Interface prototype for an application to bridge the gap between generations by facilitating an exchange of ideas over a shared meal.
        image: assets/img/projects/UI.png
        code_url: https://www.figma.com/proto/Xnu90hfv6A4YVv2qP8Yq57/Final_McCall_Craighead?node-id=117%3A2386&scaling=scale-down&page-id=19%3A1034&starting-point-node-id=117%3A2386

  - type: contact.html
    section_id: contact
    background_style: bg-primary
    title: Get in touch
    map_embed: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d887.7520702351038!2d-72.28938200098564!3d43.70400570266627!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4cb4c9dd4f758911%3A0xbdb8574c4db908cc!2sDartmouth%20College!5e0!3m2!1sen!2sus!4v1633558523587!5m2!1sen!2sus



---
