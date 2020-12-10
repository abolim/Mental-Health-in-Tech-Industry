# Mental Health in Tech Industry
An Exploratory Data Analysis

Aboli Moroney <br>
M.S Data Science at University of Washington, Seattle <br>
Research Project for DATA 512A Human Centered Data Science Course <br>
Research Timeline: 03 Nov 2020 to 10 Dec 2020 <br>

## Abstract
This repository contains an ethanographic study to understand the prevalance of mental health issues in tech industry and the measures adopted by workplaces to address these issues. It is an exploratory data analysis using survey results from respondents working in tech published by OSMI in 2019. The analysis suggests that about 84% of the respondents find the support to be inadequate and 70% may have experienced mental health issues at some point. More than 53% don't have medical coverage for mental health issues and 70% respondents shared that there are not enough forums to discuss and seek help on such topics. Majority also stated that employers give more importance to physical health over mental health and about 56% respondents don't feel completly comfortable asking for leaves for mental health issues. Overall, the study indicates that there is significant room for improvement in addressing mental health issues and overcoming the stigma of having open discussions.

## Directory Structure
```
data-512-a2
│   README.md 
│   LICENSE 
└───1-Data
│   │   OSMI 2019 Mental Health in Tech Survey Results - OSMI Mental Health in Tech Survey 2019
└───2-Analysis
|   │   EDA - Mental Health in Tech.ipynb
|   |   EDA - Mental Health in Tech.pptx
└───3-Outputs
|   │   1-Support_Tech_Mental_Health
|   │   2-Experienced_MentalHealthIssues
|   │   3-Medical_HelpResources_Mental_Health
|   │   3-Medical_HelpResources_Mental_Health_Funnel
|   │   4-Physical_vs_Mental_Health
|   │   5-LeavePolicy_Mental_Health

```
## Motivation

In January 2020, I commited to spend time on learning about and sensitizing my network of people about Mental Health and Emotional Well-being. People entering or already working the tech industry are leading increasingly stressful lives and working in highly competitive environments. In this lifestyle, self care and mental health often takes a backseat until it becomes a major medical issue. When I read the [blogs posts by OSMI](https://osmihelp.org/about/blog), I learnt several interesting facts that piqued my curiousity to perform this exploratory analysis using the survey data they published in 2019. I strongly feel that spreading awareness about Mental Health issues is a pressing need in our community and I would like to supplement my limited knowledge with scientific research.

## Purpose
This repository contains an ethanographic study using survey results from participants in tech industry published by OSMI in 2019. It explores how employees in the tech industry are affected by mental health issues and how they react to such issues. It is an effort to understand the prevelance of mental health disorders in the tech industry and the measures workplaces are adopting to address the growing concerns. 

## Data Source
The data used to perform this exploration is an open source dataset published by [Open Sourcing Mental Illness](https://osmihelp.org/about/about-osmi), a non-profit, 501(c)(3) corporation dedicated to raising awareness, educating, and providing resources to support mental wellness in the tech and open source communities. The [survey results from 2019](https://osmihelp.org/research) contain responses from over 350 participants to 82 questions. This survey was conducted to measure attitudes towards mental health in the tech workplace, and examine the frequency of mental health disorders among tech workers. The dataset can be [downloaded from Kaggle](https://www.kaggle.com/osmihelp/osmi-mental-health-in-tech-survey-2019)

## License
The original data and research is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).
The analysis peformed in this repository is licensed under MIT. Please [review the code of conduct](https://github.com/abolim/data-512-final/blob/master/LICENSE) to share, cite and repliacte this analysis.

## Research Questions
The key research areas of this project is to understand the provisions at tech workplaces to address mental health issues in employees:
  - Do employees feel that the tech industry supports mental health and wellbeing?
  - How many respondents are have experienced mental health problems or are currently being diagnosed?
  - Are employers providing healthcare benefits for mental health issues? 
  - Are employees aware of their healthcare benefits and resources?
  - How do employers weigh mental health issues at the same level as to other medical issues?
  - Are there any leave policies for those suffering from mental health issues?

## Methodology
The detailed exploratory data analysis, code, graphs, insights and observations can be found in the [Jupyter Notebook](https://github.com/abolim/data-512-final/blob/master/2-Analysis/EDA%20-%20Mental%20Health%20in%20Tech.ipynb). Each of the research questions is analyzed in depth using descriptive graphics such as bar plots, funnel plots, pivot tables, column charts for making comparisions and drawing inferences and insights are documented below the plots. Please note that some of the interactive visuals may not be visible on GitHub and can be viewed by downloading the notebook to local machine only.

## Dependencies
The following libraries are required to run the Jupyter Notebook successfully:
  plotly-orca, pandas, numpy, seaborn, matplotlib.pyplot, plotly.express

## Conclusion
Based on this ethnagraphic study, the analysis for all research questions suggests that the provisions in tech industry are not adequate for mental health issues yet. The findings and insights of this research should be generalized with caution as the survey respondents may not be a fair representation of the entire population in the tech industry and workplaces.
