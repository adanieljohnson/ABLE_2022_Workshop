## Welcome to ABLE 2022

This web page and linked GitHub repository are for the Major Workshop:

**Using Markdown and Free Online Tools to Write, Publish, and Share an Open-Source Scientific Writing Guide**

Click on the link to the repository to the left anytime you want to see the files for the workshop.

### Late Breaking News

* The STEM Writing Project is moving to a public space on the QUBES Hub. There you can find these resources and contribute to the project:
    + An overview of our Six Elements Model for teaching and assessing scientific writing.
    + Links to the open-source, multi-format Biology Writing Guide (no need to wait until May 2023 to get access via ABLE publication.)
    + Structured training activities for both students and instructors. 
    + Diagnostic activities so instructors can adjust the basic instructional strategy to local needs.
    + Automated supports that streamline routine data collection. 
        - For the NSF-sponsored project that led to SEM, we created SAWHET (STEM Automated Writing Help Tool), a web-based report collection tool. Students submitted lab reports to SAWHET, which performed basic completion checks and text analysis, then gave student tailored feedback on what was missing or might need improvement.
        - The project version used proprietary software. So we rebuilt our web form as an R Shiny app.
        SAWHET 2 is available for you to use on QUBES Hub, and the code is freely available for others to revise.
    + A collection of >4,000 de-identified biology student lab reports with metadata that can be used as:
        - Examples for training instructors; 
        - Research data for linguistic analyses, etc.;
        - Data for test other automated systems.
    + Bins-based scoring (presented at ViABLE 2021),
    + Reflective, coaching-oriented feedback,
    + Strategies for assessing student writing at BIO100 scales. 
        - We have several proxy metrics based on document features
        - We are working on automated move analysis right now

* The most recent version of R Studio has a visual R Markdown option. 
    + As best I can tell it may play well with bookdown but it also MAY NOT. So I cannot recommend using it universally yet. 
    + If you are not building books with bookdown, the visual mode means you can create and edit Markdown right in R Studio then use its embedded Pandoc tool to convert to .docx format. 
    + R Studio still writes obscenely complex .html, so I still do not recommend using it for that.
    + For now I'm sticking with my plain text editor. The fewer potential breakdown points I have, the better.
