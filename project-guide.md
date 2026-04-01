<img src="https://www.nyp.edu.sg/content/dam/nypcorp/sg/en/common/logo-nyp.svg" alt="nyplogo" width="400"/>

# ITI113 Machine Learning & Operations Project


## Unit Learning Outcomes

- Integrate machine learning knowledge to solve a real-world business problem
- Demonstrate ability to build, deploy and operationalise a practical ML solution
- Build trustworthy machine learning systems with reference to AI governance and responsible AI principles.


## Project Team

You are expected to form a project team of up to 3 members. 

- Each member should take ownership and lead his/her primary or focus area(s) (refer to later sections on descriptions of focus areas)
- Each member should be able to deliver his/her focus area(s) while providing support in other areas, and the team should complete all the associated tasks.
- Each team is expected work professionally and amicably. Marks will be deducted for individuals who rely heavily on others to complete their tasks, and/or for teams that do not work well together.
- The role of the project mentor is to provide guidance on your project proposal and to make sure you are on the right track in your project (not expected to settle disputes or disagreements in teams)

Please fill up the [online form](https://docs.google.com/forms/d/e/1FAIpQLSeD-6n_YYT-DeoNPcEv0u6HoiTz-bfNkQJJaIFh70sArY3prQ/viewform?usp=preview) of your project team members.

## Overview of Focus Areas 

| Assessment Stage | A (Data & EDA) | B (Model Dev) | C (MLOps) | D (Analysis & Comm) | AI Governance | Expected Outputs |
|-----------------|---------------|--------------|-----------|---------------------|---------------|------------------|
| **Proposal** | Problem framing, dataset identification | Define ML approach (baseline idea) | High-level pipeline design | Problem justification & business context | Initial AI risk assessment | Problem statement, dataset plan, risks identified |
| **Progress Check** | Completed EDA, cleaned dataset | Baseline model + initial evaluation | Data pipeline + experiment tracking setup | Initial results interpretation | Identify potential bias / data issues | EDA notebook, baseline results, pipeline setup |
| **Final Report** | Final dataset & feature engineering | Fine-tuned models + comparison (if applicable) | Deployment (endpoint/app), pipeline completed | Error analysis, insights, interpretation | Full governance checklist (fairness, explainability, monitoring) | Final report, deployed system, governance documentation |
| **Final Presentation** | Summary of dataset & approach | Key model results | System demo (deployment) | Clear communication of insights | Governance considerations explained | Demo + presentation of end-to-end system |

## Proposed Tasks / Workload Allocation for Team Members

| Team Size | Student Role | Primary Responsibility | A (Data & EDA) | B (Model Dev) | C (MLOps) | D (Analysis & Comm) | AI Governance |
|----------|-------------|------------------------|----------------|---------------|-----------|---------------------|---------------|
| **1 Student** | Full Stack ML | A + B + C + D | ✅ Full | ✅ Full | ✅ Full | ✅ Full | ✅ Full |
| **2 Students** | Student 1 | Model Development (B) | ✅ Main | ✅ Main | ◑ Support | ◑ Partial | ◑ Model-level (bias, explainability) |
|  | Student 2 | MLOps & Deployment (C) | ◑ Support | ◑ Support | ✅ Main | ◑ Partial | ✅ System-level (monitoring, logging, control) |
| **3 Students** | Student 1 | Model Development (Model A) | ✅ Main | ✅ Main | ◑ Support | ◑ Support | ◑ Model-level (fairness, bias checks) |
|  | Student 2 | Model Development (Model B) | ✅ Main | ✅ Main | ◑ Support | ◑ Support | ◑ Model-level (comparison, explainability) |
|  | Student 3 | MLOps & Deployment (C) | ◑ Support | ◑ Support | ✅ Main | ◑ Support | ✅ System-level (governance, monitoring, compliance) |

Performance Expectation:
- Each team must demonstrate progress across all components (A–D and AI Governance) at every assessment stage.  
- Larger teams are expected to show greater depth (e.g., multi-model comparison, pipeline automation, monitoring).  
- The expected problem complexity, model performance, and level of detailed analysis and insights should increase proportionally with team size.
- AI Governance must be addressed progressively from risk identification (Proposal) to full implementation (Final Report).

## Deliverables and Assessment Components

This project consists of the following assessment components:

| Assessment Component | Recommended Focus + Governance) | Overall (%) | Individual (%) | Total (%) |
|---------------------|--------------------------|-----------|----------------|-----------|
| **Project Proposal** | A (Problem & Data), D (Justification), Governance (Risk) | 20% | – | 20% |
| **Progress Check** | A (EDA), B (Baseline Model), C (Pipeline Setup), Governance (Bias Awareness) | 5% | 20% | 25% |
| **Final Report** | B (Tuned Models), C (Deployment), D (Analysis), Governance (Full Checklist) | 10% | 20% | 30% |
| **Final Presentation** | D (Communication), B (Results), C (System Demo), Governance (Explanation) | 5% | 20% | 25% |


**Assessment Schedule:**

- Project Proposal + Checklist - submitted by Sun 26 Jul 2026 23:59
- Project Milestone Progress Check - Submitted by Sun 16 Aug 2026 23:59  
- Final Report - submitted by Thu 27 Aug 2026 23:59
- Final Presentation - Wed 26 Aug 2026 (Online assessment)

***refer to POLITEMALL for most updated schedule***


## Project Proposal

- In the project proposal, your team will pick a business problem of your choice (or from the suggested list of projects) and formulate it as a machine learning problem.
- You are to perform risk assessment of the AI system you are developing. 
- Once you have identified the problem, it can be useful to research on some prior work or research on the related topics. 
- Another important aspect of your project is to identify one or several datasets suitable for your chosen problem. You can either use existing dataset (recommended) or collect the data yourself. (bear in mind the timeframe given that data collection effort may be significant that will impact your project completion schedule)

### Format

Project proposal should include the following information:

- Formulation[[1\]](#_ftn1): Is the problem suited for a ML solution? What is the alternative? Any heuristic you can use?  What are the appropriate success metrics? How do you frame it as machine learning problem? What are the suitable metrics to use for your model? 
- Dataset: What kind of data you need and how do you plan to collect them? If it is some existing dataset (e.g., from Kaggle), include reference link to the dataset and provide some discussion how the data was collected by the author/contributor of the dataset. 
- Discussion of data governance. 
- Methods: What kind of ML approach (e.g., supervised/unsupervised or others) are you planning to use? 
- Deployment: How do you intend to use the model? Provide an overview of how the model is used in the overall solution. You can illustrate this with a system architecture diagram. 
- AI risk assessment 
- Team members and their focus areas 


#### Grading Rubrics for Project Proposal

|  | Not Competent | Developing | Functional | Competent | Proficient |
|--|--|--|--|--|--|
|  | 0 – <10 marks | 10 – <12 marks | 12 – <14 marks | 14 – <16 marks | 16 – 20 marks |
| **Project Proposal** | * No or minimal formulation of the problem.<br>* No reference to dataset is provided or dataset given is not relevant to the problem.<br>* No ML approach is provided or incorrect approach proposed for the problem.<br>* No deployment scenario provided or lack of details on deployment.<br>* Little or no risk and impact assessment done. | * Basic problem formulation but lacks clarity.<br>* Dataset loosely relevant with minimal explanation.<br>* Basic ML approach suggested with weak justification.<br>* Limited discussion on deployment.<br>* Superficial risk and impact assessment. | * Correct problem formulation is provided.<br>* Dataset provided is somewhat relevant to the problem.<br>* Appropriate ML approach is proposed.<br>* Some discussion on how the model is to be deployed.<br>* Some assessment of the risk and impact. | * Well-defined problem formulation with consideration for alternative approaches (e.g. heuristics).<br>* Dataset provided is relevant with discussion on how the dataset is collected.<br>* Correct ML approach proposed with some discussion on other ML approaches.<br>* Clear and structured discussion on how the model is deployed in the overall solution.<br>* Clear assessment of the impact, risks, and limitations of the AI system. | * Strong and well-justified problem formulation with critical evaluation of alternatives.<br>* High-quality dataset with detailed discussion on collection, limitations, and suitability.<br>* Well-justified ML approach with comparison of multiple approaches.<br>* Detailed and realistic deployment architecture integrated into the solution.<br>* Comprehensive AI governance: clear discussion of risks, bias, ethical considerations, and mitigation strategies. |


#### Grading Rubrics for Project Proposal

|                    | Not Competent | Developing | Functional | Competent | Proficient |
| -- | -- | -- | -- | -- | -- |
|  | 0 - <10 marks | 10 - <12 marks | 12 - <14 marks | 14 - <16 marks | 16 - 20 marks |
| *Project Proposal* | 
<ul>
<li>No or minimal formulation of the problem.</li>
<li>No reference to dataset is provided or dataset given is not relevant to the problem.</li>
<li>No ML approach is provided or incorrect approach proposed for the problem</li>
<li>No deployment scenario provided or lack of details on deployment</li>
<li>Little or no risk and impact assessment done</li>
</ul> | 
<ul>
<li>Basic problem formulation but lacks clarity.</li>
<li>Dataset loosely relevant with minimal explanation.</li>
<li>Basic ML approach suggested with weak justification.</li>
<li>Limited discussion on deployment.</li>
<li>Superficial risk and impact assessment.</li>
</ul> | 
<ul>
<li>Correct problem formulation is provided.</li>
<li>Dataset provided is somewhat relevant to the problem.</li>
<li>Appropriate ML approach is proposed</li>
<li>Some discussion on how the model is to be deployed.</li>
<li>Some assessment of the risk and impact</li>
</ul> | 
<ul>
<li>Well-defined problem formulation with consideration for alternative approaches (e.g. heuristics).</li>
<li>Dataset provided is relevant with discussion on how the dataset is collected.</li>
<li>Correct ML approach proposed with some discussion on other ML approaches.</li>
<li>Clear and structured discussion on how the model is deployed in the overall solution.</li>
<li>Clear assessment of the impact, risks, and limitations of the AI system</li>
</ul> | 
<ul>
<li>Strong and well-justified problem formulation with critical evaluation of alternatives.</li>
<li>High-quality dataset with detailed discussion on collection, limitations, and suitability.</li>
<li>Well-justified ML approach with comparison of multiple approaches.</li>
<li>Detailed and realistic deployment architecture integrated into the solution.</li>
<li>Comprehensive AI governance: clear discussion of risks, bias, ethical considerations, and mitigation strategies.</li>
</ul> |

## Progress Check 

### Model Development 

You should have evaluated the suitablity of the data and finalized on the dataset. You are expected to perform extensive Exploratory Data Analysis to gain understanding of the data, and performed data cleaning, transformaion and feature engineering. You will work closely with MLOps team to help setup common data pipeline to be used in development and production. 
A baseline model should have been developed and early experimental results documented, and error analysis performed. You shoud log all the experiments using the experiment tracking facility setup by MLOps team. 

### ML Operations & Deployment 

You should have setup the MLOps platform that allows the modelling team to perform their model development and to track their experiments. You should work closely with the model development team to understand their data requirement and setup the data pipeline to ingest, clean, and transform the data suitable for model training and prediction. You should also have partially setup the MLOps platform such as model registry, and CI/CD platform. You should also work with model development to complete the relevant AI governance checklist at this stage of development. 

### Grading Rubrics 

#### Model Development (Individual - 20%)

|   | Below Expectation | Approaching Expectation | Meeting Expectation |
|:----------|:----------|:----------|:----------|
| | (0 - <7.5) | (7.5 - <12) | (12 - 15)|
| Data Understanding & Preprocessing  (15%) | <ul><li>Minimal or no exploratory data analysis</li><li>Minimal or no data preparation done</li></ul> | <ul><li>Some exploratory data analysis done with some discussion</li><li>some data preprocessing done</li></ul> | <ul><li>Signifcant amount of exploratory data analysis with insighful discussion</li><li>Significant amount of data preparation</li></ul> |
| | (0 - < 2.5) | (2.5 - < 4) | (4 - 5)
| Modelling  (5%)  | <ul><li>Inappropriate choice of algorithms for the chosen problem</li><li>Minimal or no model experimentation is done | <ul><li>appropriate choice of algorithm for the chosen problem</li><li>Some model experimentation is done with reasonable result</li></ul>  | <ul><li>appropriate choice of algorithm with clear justification and consideration of ai governance aspects</li><li>Some early model experimentation results with clear interpretation and good performance exceeding baseline</li></ul> |

# 📊 Grading Rubrics  
## Model Development (Individual – 20%)

| Criteria | Not Competent | Developing | Functional | Competent | Proficient |
|----------|--------------|------------|------------|-----------|------------|
| **Data Understanding & Preprocessing (15%)** | (0 – <6) <br> • Minimal or no exploratory data analysis <br> • Minimal or no data preparation | (6 – <9) <br> • Limited EDA with superficial observations <br> • Basic preprocessing with gaps or errors | (9 – <12) <br> • Adequate EDA with some insights <br> • Reasonable preprocessing completed | (12 – <14) <br> • Good EDA with clear insights and patterns identified <br> • Well-executed preprocessing and feature preparation | (14 – 15) <br> • Extensive and insightful EDA uncovering non-obvious patterns <br> • Advanced preprocessing and feature engineering with strong justification |
| **Modelling (5%)** | (0 – <2) <br> • Inappropriate or no model used <br> • No meaningful experimentation | (2 – <3) <br> • Basic model selected with weak justification <br> • Limited experimentation with poor results | (3 – <4) <br> • Appropriate model selected <br> • Some experimentation with reasonable results | (4 – <4.5) <br> • Appropriate model with clear justification and consideration of AI governance <br> • Good performance exceeding baseline with clear interpretation | (4.5 – 5) <br> • Strong model selection with comparison or tuning <br> • High performance with deep interpretation, limitations discussed, and governance considerations clearly integrated |


#### Model Operations & Deployment (Individual - 20%)

|   | Below Expectation | Approaching Expectation | Meeting Expectation |
|:----------|:----------|:----------|:----------|
| | (0 - <7.5) | (7.5 - <12) | (12 - 15)
| MLOps Pipeline (15%)| <ul><li>No data pipeline is defined or or data pipeline has errors</li><li>No experimentation logging setup</li><li>Minimal features or no features setup for MLOps platform</li></ul> | <ul><li>Appropriate data pipeline is setup and works partially</li><li>Experiment logging available</li><li>Model registry is available for model versioning| <ul><li>Complete and working data pipeline</li><li>Extensive logging facility available with dashboard / visualization</li><li>Model registry and CI/CD pipeline is setup</li></ul> |
| | (0 - < 2.5) | (2.5 - < 4) | (4 - 5)
| AI governance checklist (5%)  | <ul><li>No checklist or minimal checklist completed</li><li>Explanation given in checklist is irrelevant or contains errors</li></ul> | <ul><li>Some checklist items completed</li><li>Explanation given in checklist is mostly relevant and correct</li></ul>  | <ul><li>Most checklist items relevant for the given project cycle is completed</li><li>Explanation given in the checklist is relevant and correct.</li></ul> |

#### Group (10%)

| | Below Expectation | Approaching Expectation | Meeting Expectation |
|:----------|:----------|:----------|:----------|
| | (0 - <4) | (5 - <8) | (8 - 10) | 
| Team work | Little or no coordination between members in model development process or no coordination between model and mlops members | Some coordination between members in the model development process, or coordination between development operation team in defining the data pipeline, model experimentation tracking and CI/CD pipeline | Very close coordination within the model development team, or between the model development and operation team in defining the data pipeline, model experimentation tracking and CI/CD pipeline | 

- *Group score for 1-person team will evaluate how well the different parts are integrated and working together.
  
## Final Report

Each team should submit one combined Final report. The report should include the following sections: 

- ML Formulation
  - Here you can briefly describe the ML framing of the problem. Clearly state what the input and output is, and the kind of ML model used (e.g., regression, classifier, etc.).  

- Data Preparation & Feature Engineering
  - Here you should describe the feature set used for your modeling. Describe the insights you gained from the dataset and how you engineer the feature set for modelling. Describe any potential bias and how you mitigate the bias. 

- Modelling and Experiments
  - Here you can describe the different models (and corresponding feature set) you have experimented with. This should not be a listing of experimental results. The report should focus on what is your hypothesis, what model you are using to test the hypothesis, error analysis, observations, and performance tuning. 
  - As a team, each member may conduct different experimentations using different algorithms. Each member can describe their experimentations in different subsection and clearly stated the name of the member contributing to the section.

- ML Operations & Deployment
  - Describe the ML pipeline that has been setup, including the data pipeline, model registry, CI/CD and data and model drift monitoring, and any additional features available
  - describe the demo application, including application architecture, technology stack you used, and other relevant details.

- Test Report 
  - provide test results of relevant tests for your use case, such as fairness, explanability and robusness test (e.g. those generated by AI Verify toolkit)

- AI governance checklist 
  - completed checklist (e.g. report from AI verify toolkit or the ISAGO checklist)

- Project artifacts 
  - link to the git repository for your code (the jupyter notebook) and link to your demo app. 

**Note** 
- clearly mark the section contributed by each member
- use the font size of 12, times new roman, single column.
- the main content (excluding cover page, TOC and appendix) should not be more than 20 pages. Only highlight the key info, the details can be parked under appendix.
  
### Grading Rubrics

#### Model Development Focus (Individual - 20%)

|   | Below Expectation | Approaching Expectation | Meeting Expectation |
|:----------|:----------|:----------|:----------|
| | (0 - <4) | (5 - <8) | (8 - 10)|
| Data (10%) | <ul><li>No or minimal data analysis provided</li></ul> | <ul><li>Good data analysis provided with some insights</li></ul> | <ul><li>Excellent data analysis with very insighful discussion</li><li>Analysis of potential data bias and mitigation techniques</li></ul> |
| | (0 - <4) | (5 - <8) | (8 - 10)
| Modelling (10%) | <ul><li>Little or no explanation of choice of algorithms</li><li>Minimal or no discussion of experimental results | <ul><li>Good explanation of algorithms used</li><li>Good discussion of experimental results</li></ul>  | <ul><li>Excellent discussion of algorithmic choice and the resultant trade-off</li><li>Excellent discussion of the experimental results and the performance tuning done</li></ul> |


#### Model Operations & Deployment Focus (Individual - 20%)

|   | Below Expectation | Approaching Expectation | Meeting Expectation |
|:----------|:----------|:----------|:----------|
| | (0 - <2.5) | (2.5 - <4) | (4 - 5)
| MLOps Pipeline (5%) | <ul><li>No or minimal description of the ML pipeline setup </li></ul> | <ul><li>Clear description of the ML pipeline setup, which supports model development and deployment| <ul><li>Very clear description of the ML pipeline setup to support model development and deployment</li>|
| Demo Application (5%)  | <ul><li>minimal or no description of the application works</li></ul> | <ul><li>Clear description of the application, with explanation of the interfacing with the models</li></ul>  | <ul><li>Very clear description of the application and the features provided, the application architecture including the integration with the models, and description of how it enable continuous training </li></ul> |
| AI governance checklist  (5%) | <ul><li>No checklist or minimal checklist completed</li><li>Explanation given in checklist is irrelevant or contains errors</li></ul> | <ul><li>Some checklist items completed</li><li>Explanation given in checklist is mostly relevant and correct</li></ul>  | <ul><li>Completed checklist for all required items</li><li>Explanation given in the checklist is relevant and correct.</li></ul> |
| Test Result (5%) | No test result given or incomplete test result | Complete and relevant test result given | Complete and relevant test result given and good explanation of the test result | 

#### Group 

| | Below Expectation | Approaching Expectation | Meeting Expectation |
|:----------|:----------|:----------|:----------|
| | (0 - <2.5) | (2.5 - <4) | (4 - 5) | 
| Problem formulation (5%) | Unclear ML formulation | Clear ML formulation, and includes heuristics | Very clear ML formulation, with heuristics, and discussion of metrics used to measure success | 
| Team work (5%)| Inconsistent report formatting | somewhat consistent report formatting | very consistent report formatting with clear indication of contribution of each members |  


## Final Presentation

During final presentation, you will be jointly assessed by more than one supervisor to ensure fairness in assessment. Among other things, you are required to show and explain the work you have done. You will be assessed based on your demonstrated understanding of the methodologies used and discussion of the experimental results.



### Grading Rubrics

| | Below Expectation | Approaching Expectation | Meeting Expectation |
|:----------|:----------|:----------|:----------|
| | 0 - <2.5  | 2.5 - <4 | 4 - 5|
| Presentation (Group) (5%) | <ul><li>No coordination among members</li><li>Incoherent presentation flow</li></ul><br/>| <ul><li>Some coordination among members</li><li>Presentation flow is evident</li></ul><br/> | <ul><li>Good coordination among members</li><li>Presentation flow is clear and very clear task division.</li></ul><br/>
| | 0 - <10 | 10 - <16 | 16 - 20 | 
| Presentation (Individual) (20 %) | <ul><li>Unable to present the content or incoherent presentation</li><li>Unable to answer most of the questions</li></ul> | <ul><li>Somewhat clear and coherent presentation</li><li>Able to answer some questions with some hesitation</li></ul> | <ul><li> Clear and coherent presentation with demo of application / deployment</li><li>Able to answer all or most of the questions confidently</li></ul> |

## Project mentors

The project teams will be jointly supervised by a group of project mentors. The project mentors and the contact info are listed below.

| Name                              | Contact |
|:----------|:----------|
| Mr. Mar Kheng Kok (Course Manager / Project Mentor) | refer to POLITEMALL |
| Dr. Leong Siang Huei (Module Leader / Project Mentor) | refer to POLITEMALL |
| Dr. Brandon Ooi (Project Mentor)  | refer to POLITEMALL |
| Mr. Wee Chee Hong (Project Mentor)  | refer to POLITEMALL |
| Mr. Lee Ching Yuh (Project Mentor)  | refer to POLITEMALL |
| Mr. Steven Ng (Project Mentor) | refer to POLITEMALL |

## Project Schedule


| Week | Monday | Wed | Thur|
|:----------|:----------|:----------|:----------|
| 13 | | |**16-Jul-26**<br/> Project Initiation / Consultation (F2F) <br/> (MKK/LSH) |                                                               
| 14 | | |**23-Jul-26**<br/> Project Consultation (F2F) - <br/> (MKK/LSH) |                                                               
| 15 | | |**30-Jul-26**<br/> Project Dev / Consultation (Zoom) <br/> (MKK/LSH) |                                                               
| 16 | | |**6-Aug-26**<br/> Project Dev / Consultation (Zoom, by appointment only) <br/> (LSH) |                                                               
| 17 | | |**13-Aug-26**<br/> Project Dev / Consultation (Zoom, by appointment only - <br/> (MKK) | 
| 18 | **17-Aug-26**<br/> Progress Check (Zoom) <br/> (MKK/LSH) | **19-Aug-26**<br/> Project Dev / Consultation (Zoom, by appointment only) <br/> (LSH)| **20-Aug-26**<br/> Project Dev / Consultation (Zoom, by appointment only) <br/> (MKK) |
| 19   | **24-Aug-26**<br/> Project Dev / Consultation (Zoom) <br/> (MKK/LSH) | **26-Aug-26**<br/> **Project Presentation** (**Zoom**) <br/> (MKK/LCY/LSH/BRO/WCH/SNG) | **27-Aug-26** <br/> *Final Repot Submission* |


**Legends**

- ALL - All tutors
- MKK - Mr. Mar Kheng Kok
- LCY - Mr. Lee Ching Yuh
- LSH - Dr. Leong Siang Huei
- BRO - Dr. Brandon Ooi
- WCH - Mr. Wee Chee Hong
- SNG - Mr. Steven Ng


[[1\]](#_ftnref1) Refer to the Lesson 3 lecture notes on ML framing 
