# Supplementary Material: Analyzing the Importance of JabRef Features from the User Perspective

This repository includes data and other materials associated with a Workshop Paper from the 11th Central European Workshop on Services and their Composition (ZEUS) held in 2019.

>JabRef is a reference management system mostly used by LaTeX users to organize their bibliographic references. As it is often the case in free and open source software, the usability of this program has not yet been analyzed systematically. In this paper, we report on the first application of user-centered design methods in this project. To identify the important features of JabRef, we first analyzed the telemetry data and then conducted an online survey with 124 participants. The analysis of the responses shows that the features naturally fall into groups based on the feature's perceived importance and the user's awareness of it. Finally, we derive guidelines on how to improve JabRef's user interface.

### Cite as
Simon, Martin K.; Dietz, Linus W.; Diez, Tobias & Kopp, Oliver: *Analyzing the Importance of JabRef Features from the User Perspective.* Proceedings of the 11th Central European Workshop on Services and their Composition, 2019. 

## Files
In the following, you can find information on the files in this repository and their content.

### Simon2019.pdf

This document contains the Master's thesis of Martin K. Simon at the Technical University of Munich, which gives further in-depth analysis of the online survey and other efforts made to improve the usability of JabRef.

Thesis abstract:

>The goal of this thesis is to improve the usability of JabRef, a free and open source reference management software, which processes references in the BibTeX format and is mainly targeted at LaTeX users. To achieve that goal, we proceeded in accordance with the user-centered design process by involving users in our work and employing principles of software ergonomics. As the first step, we identified the most important features of JabRef from a user perspective, through an online questionnaire with 101 respondents, which revealed that JabRef's entry editor and group feature should be prioritized. We then performed a laboratory study with six participants, consisting of a thinking aloud experiment for both features and a card sorting task targeting the parts of the entry editor. Lastly, we performed an expert assessment of the JabRef interface to identify more general usability problems, but it also led to the main menu being prioritized in our future work. On the basis of our findings, suggestions for changes in JabRef's main menu, entry editor, and group feature were made in accordance with usability principles. To support the recommendations, high fidelity prototypes of the reworked user interface parts were created. To integrate our findings into the open source development process, we presented them in a standardized digital format on Github and divided redesign suggestions into multiple smaller packages.

### onlineSurvey.pdf

This document contains a PDF version of the online survey that was conducted with JabRef users. The text and content structure are the same as in the online version, which was distributed as a Google Form.

### surveyData.csv

This file contains the data, which was obtained from the answers to the survey in _onlineSurvey.pdf_. For reasons of data protection, two columns were removed from the data:

- A timestamp of the answers
- The answers to the question _"Would you like to tell us anything else?"_, because they contained identifying information.

Every row of the data contains one answer to the survey. So every row equals the data of one respondent.
The content of the columns is as follows:

- Column 1-24 contain the importance ratings of the 24 investigated JabRef features as text. The column header describes which feature was rated.
- Column 25&26 contain the answers to the free text questions in the survey. The column header shows the question text.
- Column 27-30 contain the demographical information of the respondent regarding their use of JabRef. The informtion is saved as text. The column header shows the question text from the survey.
