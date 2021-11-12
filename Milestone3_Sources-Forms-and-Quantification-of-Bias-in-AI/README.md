This milestone is being led by Roseline Polle. It should take approximately four hours to complete. 

In this milestone, we start looking at some technical aspects of bias and fairness in AI: given a machine learning problem, how can we assess and measure bias? What are the different types of bias and where do they come from? The session, after the introduction video, is divided in two main parts:

[Introduction video](https://youtu.be/2w93PohBQ-o)

**Part 1: Theory** (_4 videos with slides + supporting "cheatsheet" notebook_)
- [Cheatsheet Notebook](https://colab.research.google.com/drive/14IW87BJyAc9Cgtxf2Fov-iJB2rgDUeIK)
- [Theory 1: Real-life examples of bias in algorithms](https://youtu.be/NF8VRGJDI_g)
- [Theory 2: Sources of Bias](https://youtu.be/k6LGIngVhac)
- [Theory 3: Fairness definitions and metrics](https://youtu.be/m3zpMJ6Y7Ec)
- [Theory 4: Choosing a metric](https://youtu.be/_snpZmLfVlk)

**Part 2: Practice** (_4 notebooks_)

We look at a specific Supervised Learning problem where a company uses an algorithm in their hiring process to decide which candidates go to the next round. Candidates are labelled either "pass" (0) or "fail" (1).  This part contains 4 separate notebooks:
<!-- - [Notebook 1: Explore the given data: find label distribution per group and look for proxies](https://colab.research.google.com/drive/17X2XUo82zIROwuEU0KUylCJGAr7TAco5)
- [Notebook 2: Measure model bias "by hand" using the following metrics: Statistical Parity, Disparate Impact, Equal Opportunity Difference](https://colab.research.google.com/drive/179V-zinJPttr4xIzFOgxsGgm2Z62Boco)
- [Notebook 3: Measure model bias using aif360](https://colab.research.google.com/drive/1BJK41oaJRmegdoh4TKp0XfrrXZPF4TRI)
- [Notebook 4: Use bootstrap sampling to get a confidence interval for each metric](https://colab.research.google.com/drive/1fBugsn1-6JknonL-DJMFacmyhc1BtyqG)
-->
- [Notebook 1: Explore the given data: find label distribution per group and look for proxies](https://colab.research.google.com/github/alan-turing-institute/bias-in-AI-course/blob/main/Milestone3_Sources-Forms-and-Quantification-of-Bias-in-AI/notebooks/M3_Practice_1_Explore_data.ipynb)
- [Notebook 2: Measure model bias "by hand" using the following metrics: Statistical Parity, Disparate Impact, Equal Opportunity Difference](https://colab.research.google.com/github/alan-turing-institute/bias-in-AI-course/blob/main/Milestone3_Sources-Forms-and-Quantification-of-Bias-in-AI/notebooks/M3_Practice_2_Evaluate_fairness_metrics_manually.ipynb)
- [Notebook 3: Measure model bias using aif360](https://colab.research.google.com/github/alan-turing-institute/bias-in-AI-course/blob/main/Milestone3_Sources-Forms-and-Quantification-of-Bias-in-AI/notebooks/M3_Practice_3_Evaluate_fairness_metrics_with_aif360.ipynb)
- [Notebook 4: Use bootstrap sampling to get a confidence interval for each metric](https://colab.research.google.com/github/alan-turing-institute/bias-in-AI-course/blob/main/Milestone3_Sources-Forms-and-Quantification-of-Bias-in-AI/notebooks/M3_Practice_4_Example_code_get_a_confidence_interval.ipynb)


**Practice Instructions:** <br>
You can chose to download the notebooks on your machine and use them with Jupyter, or open them directly through Google Colab by clicking on the links above. 

If the latter:
- Make sure you copy them in your own Google Drive as the original files are not editable.

If you use the notebooks locally:
- The data can be downloaded here: https://docs.google.com/uc?export=download&id=1-Wd1evAoDs4YsjRLfC-ifarmQL-Ozg3R. 
- Make sure to save the data in the same folder as the notebooks. 
