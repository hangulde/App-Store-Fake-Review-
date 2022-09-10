App Store Fake Review Detection



File structure


Notebooks: Each stage was conducted in seperate notebooks.

Data wrangling
Exploratory data analysis
Univariate models
Multivariate models
Media: Includes media which are used in report.

Report: Pdf of project report.

Presentation: pdf and pptx format of presentation

The fake reviews dataset is split into three files:
- reviews.json: Includes the fake and official reviews
- apps.json: Includes meta-data (e.g., price) of apps related to the reviews
- features.json: Includes the extracted machine learning features as described in the paper (e.g., length of reviews) and a label indicating if the review if as fake review (label = 1) or official review (label = 0).


@Article{Martens2019,
author={Martens, Daniel
and Maalej, Walid},
title={Towards understanding and detecting fake reviews in app stores},
journal={Empirical Software Engineering},
year={2019},
month={Dec},
day={01},
volume={24},
number={6},
pages={3316-3355},
issn={1573-7616},
doi={10.1007/s10664-019-09706-9},
url={https://doi.org/10.1007/s10664-019-09706-9}
}


