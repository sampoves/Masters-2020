# Parking private cars and spatial accessibility in Helsinki Capital Region – Parking time as a part of the total travel time

Welcome to view **the source code of my master's thesis** (University of Helsinki, Faculty of Science, Department of Geosciences and Geography). In this repository, you can view the thesis writing process from the establishment of the LaTeX document framework in February 2019 to the last finishing touches made in October 2020.

To my knowledge, an overwhelming majority of master's theses in the University of Helsinki are written in Microsoft Word. I had little interest in managing a project of this size in Word for many reasons, and luckily, I found out about LaTeX and Overleaf in late 2018. LaTeX, in short, is a document preparation system, used to create documents such as scientific articles. With a large amount of software packages available, LaTeX can provide a reliable and flexible foundation for a lengthy document while giving it a professional appearance. This thesis was entirely written in the online LaTeX editor [Overleaf](https://www.overleaf.com/).

The thesis is available as PDF at the Digital Repository of the University of Helsinki: **http://urn.fi/URN:NBN:fi:hulib-202010304366**

## Writing a thesis in LaTeX

By the time I had finished this thesis, I was a complete LaTeX convert. There are some major advantages in using LaTeX (and Overleaf, or a competing online LaTeX editor) in just about any literary work. For me, the most important feature Overleaf offered was the GitHub integration which enabled saving the entire version history of my thesis process for the posterity. Additionally, the programmatic nature of LaTeX leaves less room for human error when compared to Word. Word hallmarks such as irregular line spacing, fonts, and font sizes, accompanied with awkward positioning of basic elements such as figures and tables are not a thing in LaTeX.

As I found LaTeX so useful in my thesis work, I created a template version of my thesis in Overleaf. In this Overleaf template project, I demonstrate some of the most useful features I employed in my thesis without the clutter of actual body text. Take a look at the template at https://github.com/sampoves/msc-thesis-template.

### LaTeX woes

Not all is fluffy in LaTeX land, not at least with my somewhat novice skillset. Here are some problems I encountered during the development of this LaTeX document:

* The Mendeley integration for synchronisation of references was problematic. The Mendeley application itself stores a great amount of information about sources, but one can't import most of them to Overleaf. In the end, I had to synchronise the list of references one final time, then duplicate the file ``references.bib`` and make final adjustments to ``references_final.bib``.
* For my purposes, the references package ``natbib`` proved a poor choice. It seems that the package is programmed in a rigid way, thwarting any attempts in creating custom bibliography styles.
* In my experience, table building can be finicky in LaTeX. I had to combat with some details, such as the justification of text inside cells, horizontal and vertical positioning of text in cells and the somewhat hard to decipher syntax of the packages ``tabular`` and ``tabularx``.
* The appearance of the chapter *appendixes* is produced in a somewhat hacky way. Most of the settings for *appendixes* had to be created in the document preamble in ``main.tex``. This lead to a pretty appearance, but the insides are held together with bubblegum. For example, in the final thesis PDF all appendixes have a untitled bookmark.

## Associated repositories

### Primary repositories

Please find the other GitHub repositories important to this thesis in the table below.

| Repository | Description | Web deployment |
| --- | --- | --- |
| https://github.com/sampoves/thesis-data-analysis | The thesis data analysis workflow, the main repo for all things programming in this thesis | See below |
| https://github.com/sampoves/parking-in-helsinki-region | The web based survey application | Hosted by the author: **https://parking-survey.socialsawblade.fi** |
| https://github.com/sampoves/thesis-analysis-shinyapps | shinyapps.io deployment of the survey data analysis and statistics application | shinyapps.io: **https://sampoves.shinyapps.io/analysis/** |
| https://github.com/sampoves/thesis-visitors-shinyapps | shinyapps.io deployment of the visitors analysis application | shinyapps.io: **https://sampoves.shinyapps.io/visitors/** |
| https://github.com/sampoves/thesis-comparison-shinyapps | shinyapps.io deployment of the travel time comparison application | shinyapps.io: **https://sampoves.shinyapps.io/comparison/** |

### Appendixes

During the process of creating the thesis, the following side products came into being:

| Repository | Description | Language(s) |
| --- | --- | --- |
| https://github.com/sampoves/leaflet-map-survey-point | A variant of the survey application. Users place points on the map instead of postal code areas | HTML, Javascript, PHP |
| https://github.com/sampoves/msc-thesis-template | A barebones LaTeX thesis template in the style required by Department of Geosciences and Geography in the University of Helsinki | LaTeX |

## Sonic landscapes

This thesis was written while immersed in the deep sonic landscapes produced by some unbelievably talented ambient, downtempo, and psychill artists and projects: [Atmoswaves](https://mindspringmusic.bandcamp.com/album/distant-horizons), [Solar Fields](https://solarfields.bandcamp.com/album/altered-second-movements), [Carbon Based Lifeforms](https://carbonbasedlifeforms.bandcamp.com/album/twentythree), [Lauge](https://iboga-beatspace.bandcamp.com/album/dawn), [Stellardrone](https://stellardrone.bandcamp.com/album/between-the-rings), [Atmoflow](https://atmoflow.bandcamp.com/album/transparence), [Connect.Ohm](https://ultimae.bandcamp.com/album/9980), [Dreamstate Logic](https://dreamstatelogic.bandcamp.com/album/secrets-of-the-stars), [Neuroq](https://mysticsound.bandcamp.com/album/neuroq-spacephoria-3), [Dreaming Cooper](https://dreamingcooper.bandcamp.com/album/exploring-the-universe), [Cell](https://ultimae.bandcamp.com/album/hanging-masses), and [Distant System](https://distantsystem.bandcamp.com/album/spiral-empire).
