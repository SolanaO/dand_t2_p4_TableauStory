# PISA2012 - A Tableau Story

## Summary

PISA is an international survey of students' skills and knowledge in reading, mathematics and science as they approach the end of compulsory education. In 2012 around half million students from more than 60 countries took this complex set of tests. In this report, PISA 2012 will be used to investigate the differences in achievement in mathematics tests based on location, gender and student attitudes.

## Design

The design of the Story is based on two factors: the main message/idea of the story (as described in the summary) and the possible audience for the presentation. It is assumed that the audience has some basic statistical knowledge and some interest or experience with math education.

After an initial description of the context, it is emphasized how certain metrics (such as math proficiency scores, indices that measure attitude towards math) differ with gender and location. The main measure to work with is the math proficiency score. In order to avoid information overload, only three indices are chosen from the long list of options which measure various attitudes towards math. These are math anxiety, math interest and math intentions.

Maps with highlighting options and bubble graphs are used to give a visual understanding on how the variables are changing with location.

The PISA testing process is quite complex, the literature is extensive and it is the author's opinion that some specific information has to accompany the visualizations. This includes details on the mathematics proficiency levels and on how several mathematics indices are computed. This information is inserted as text boxes in dashboards.

To enhance the visual appearance of the Story various types of graphs are used, the gender is color coded and filters are provided to the reader. Numerical details are included in tooltips.

Two types of numerical information are used, one that is based on percentages and the second that is based on actual counts. In the author's opinion alternating between the two approaches will encourage a conversation on how various countries participate in the survey, how the data is distributed worldwide and on genders and how statistically accurate this information is.

For clarity and conciseness some of the variables and abbreviations are renamed, the tooltips and the axes names are edited.

## Data Files

* pisadict2012_clean.csv - cleaned and trimmed list of codes and abbreviations;
* PISA_dataWrangle.ipynb - Jupyter notebook with Python code used to wrangle the two data files;
* PISA_dataWrangle.html - the html version of the notebook;
* tableauStory_outline.ipynb - this Jupyter Markdown document, contains a description of the project;
* tableauStory_outline.html - the html version of the Markdown document.

[Link to Tableau Story](https://public.tableau.com/shared/JXW9F5PRY?:display_count=yes)
