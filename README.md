# Data and code for _The Role of Text in Visualizations: How Annotations Shape Perceptions of Bias and Influence Predictions_

_Chase Stokes ([cstokes@ischool.berkeley.edu](mailto:cstokes@ischool.berkeley.edu))_<br>
_Cindy Xiong ([cxiong@u.northwestern.edu](mailto:cxiong@u.northwestern.edu ))_<br>
_Marti Hearst ([hearst@berkeley.edu](mailto:hearst@berkeley.edu))_<br>

This repository contains supplementary materials for _The Role of Text in Visualizations: How Annotations Shape Perceptions of Bias and Influence Predictions_.

## Repository contents

Each study folder contains at least an analysis foler, a stimuli images folder, and a survey materials folder.

- **[tables.pdf](tables.pdf)**: pdf file containing comparisons of baseline and fully saturated mixed effect models. Captions describe which study each table corresponds to. 
- **[study 1/](study 1/)**: folder containing all files pertaining to Study 1
- - **[analysis/](analysis/)**: folder containing all analysis files for Study 1
- - - *[study 1 data.csv](study 1 data.csv)*: survey output for Study 1 participants
- - - *[study-1-response-visualizations.pdf](study-1-response-visualizations.pdf)*: streamlined file displaying visualizations of the  response count and spread
- - - *[full study 1 analysis.Rmd](full study 1 analysis.Rmd)*: analysis script for all of Study 1, including exploratory analysis
- - - *[full-study-1-analysis.pdf](full-study-1-analysis.pdf)*: knit Rmd file containing all of Study 1 analysis
- - **[stimuli images/](stimuli images/)**: folder containing all stimuli images for Study 1. split into bar and line chart folders, each containing control/L1, L2, L3, and L4 folders
- - **[survey materials/](survey materialss/)**: folder containing example survey for Study 1
- - - *[study 1 example.pdf](study 1 example.pdf)*: example survey for Study 1, displaying a Blue L2 bar chart as the potential stimulus

- **/study 2**: folder containing all files pertaining to Study 2
- - **/analysis**: folder containing all analysis files for Study 2
- - - **/power analysis**: folder containing the power analysis files for Study 2
- - - - *study 1 data.csv*: survey output for Study 1 participants
- - - - *study 2 power analysis.Rmd*: power analysis simulations for study 2 & exploration of potential outcomes
- - - *study 1 data.csv*: survey output for Study 1 participants
- - - *study 2 data.csv*: survey output for Study 2 participants
- - - *study-2-response-visualizations.pdf*: streamlined file displaying visualizations of the  response count and spread
- - - *full study 2 analysis.Rmd*: analysis script for all of Study 2, including exploratory analysis
- - - *full-study-2-analysis.pdf*: knit Rmd file containing all of Study 1 analysis
- - **/stimuli images**: folder containing all stimuli images for Study 2. split into bar and line chart folders, each containing blue and green subfolders for high, low, and no-side bias
- - **/survey materials**: folder containing example survey for Study 2
- - - *study 2 example.pdf*: example survey for Study 2, displaying a Green High Bias bar chart as the potential stimulus
- - **/annotation collection**
- - - **/analysis**: folder containing all data and anaysis files for the ratings of collected annotations
- - - - *all_annotations.csv*: set of 102 annotations, their average ratings, prompt, chart type, and other data (e.g., standard error, no-side code)
- - - - *annotations_text.csv*: set of 102 annotations, the prompt group, number in the survey, and other data (e.g., no-side code)
- - - - *bar.csv*: survey output (wide) for each participant's ratings of the annotations for the bar charts
- - - - *line.csv*: survey output (wide) for each participant's ratings of the annotations for the line charts
- - - - *annotation_ratings.Rmd*: analysis script for selecting the Study 2 annotations
- - - **/survey materials**: folder containing example surveys for annotation collection and rating
- - - - *annotation_collection_example.pdf*: example survey for the collection of the annotations
- - - - *annotation_rating_example.pdf*: example survey for the rating of the annotations
- [replicability_stamp/](replicability_stamp/): Files submitted for the [Replicability Stamp](http://www.replicabilitystamp.org/requirements.html)

## Supplementary Material References

Below are all sections which reference the supplementary materials and which materials to look at to address these sections:

- Section 3.3: The example study 1 survey can be found in study 1/survey materials/study 1 example.pdf
- Section 3.4: Detailed study 1 analysis can be found in study 1/analysis/full study 1 analysis.Rmd or study 1/analysis/full-study-1-analysis.pdf. Model tables can be found in tables.pdf in the main directory.
- Section 3.4.2: Mixed effects model tables can be found in tables.pdf in the main directory. Analysis code can be found in study 1/analysis/full study 1 analysis.Rmd
- Section 4.2: Study 2 stimuli information can be found in study 2/stimuli images
- Section 4.3: The example study 2 survey can be found in study 2/survey materials/study 2 example.pdf
- Section 4.4: Detailed study 2 analysis can be found in study 2/analysis/full study 2 analysis.Rmd or study 1/analysis/full-study-2-analysis.pdf. Model tables can be found in tables.pdf in the main directory.

Contact [Chase Stokes](mailto:cstokes@ischool.berkeley.edu) with any questions or requests for additional materials from this project.
