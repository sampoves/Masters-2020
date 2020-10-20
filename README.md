# Parking private cars and spatial accessibility in Helsinki Capital Region – Parking time as a part of the total travel time

Welcome to view the source code of my master's thesis (University of Helsinki, Faculty of Science, Department of Geosciences and Geography). In this repository, you can view the thesis writing process from the establishment of the LaTeX framework in February 2019 to the last finishing touches made in October 2020.

To my knowledge, an overwhelming majority of master's theses in the University of Helsinki are written in Microsoft Word. I had little interest in managing a project of this size in Word for many reasons, and luckily, I found out about LaTeX and Overleaf in late 2018. LaTeX, in short, is a document preparation system, used to create documents such as scientific articles. With a large amount of software packages available for it, LaTeX can provide a reliable foundation for a lengthy document while giving it a professional appearance. This thesis was entirely written in the online LaTeX editor [Overleaf](https://www.overleaf.com/).

The thesis is available as PDF at University of Helsinki E-thesis: https://ethesis.helsinki.fi/en/ **(NB: the thesis not yet published)**

## Writing a thesis in LaTeX

By the time I had finished this thesis, I was a complete LaTeX convert. There are some major advantages in using LaTeX (and Overleaf, or a competing online LaTeX editor) in just about any literary work. For me, the most important feature Overleaf offered was the GitHub integration which enabled saving the entire version history of my thesis process for the posterity. I know of no other thesis developed in this way. Additionally, the programmatic nature of LaTeX leaves less room for human error when compared to Word. Word hallmarks such as irregular line spacing, fonts, and font sizes, accompanied with awkward positioning of basic elements such as figures and tables just are not a thing in LaTeX.

### LaTeX woes

Not all is fluffy in LaTeX land, not at least with my somewhat novice skillset. Here are some problems I encountered during the development of this LaTeX document:

* The Mendeley integration for synchronisation of references was problematic. The Mendeley application itself stores a great amount of information about sources, but one can't import most of them to Overleaf. In the end, I had to synchronise the list of references one final time, then duplicate the file ``references.bib`` and make final adjustments to ``references_final.bib``.
* For my purposes, the references library ``natbib`` proved a poor choice. It seems that the package is programmed in a rigid way, thwarting any attempts in creating custom bibliography styles.

## Associated repositories

Please find the other GitHub repositories important to this thesis in the table below.

| Repository | Description | Web deployment |
| --- | --- | --- |
| https://github.com/sampoves/thesis-data-analysis | The thesis data analysis workflow | See below |
| https://github.com/sampoves/parking-in-helsinki-region | The web based survey application | Hosted by the author: **https://parking-survey.socialsawblade.fi** |
| https://github.com/sampoves/thesis-analysis-shinyapps | shinyapps.io deployment of the survey data analysis and statistics application | shinyapps.io: **https://sampoves.shinyapps.io/analysis/** |
| https://github.com/sampoves/thesis-visitors-shinyapps | shinyapps.io deployment of the visitors analysis application | shinyapps.io: **https://sampoves.shinyapps.io/visitors/** |
| https://github.com/sampoves/thesis-comparison-shinyapps | shinyapps.io deployment of the travel time comparison application | shinyapps.io: **https://sampoves.shinyapps.io/comparison/** |

During the process of creating the thesis, the following side products came into being:

| Repository | Description | Language(s) |
| --- | --- | --- |
| https://github.com/sampoves/leaflet-map-survey-point | A variant of the survey application. Users place points on the map instead of postal code areas | HTML, Javascript, PHP |
| https://github.com/sampoves/msc-thesis-template | A barebones LaTeX thesis template in the style required by Department of Geosciences and Geography in the University of Helsinki | LaTeX |
