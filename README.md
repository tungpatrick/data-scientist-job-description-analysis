# Data Scientist Job Description Analysis

![](img/WordCloud.png)

<hr>

I am currently in the process of a job hunt for a data scientist/analyst job. While in the process, I thought that it might be interesting to see if there is a way for me to determine what might be the essential skills or key skills that data scientists must have that employers are looking for.

The repo contains the [Jupyter notebook](/job_posting_analysis.ipynb) and [job description postings](/data/job_text.csv) collected from Indeed. Of course, if you would like to create a web scraper that collects other job postings, the code can be easily modified in the Jupyter notebook. The notebook will walk through collecting job postings, preprocessing text, keyword extractions, and clustering of job postings. I also provide my insights of what I have found throughout my analysis.

As a quick visualization, I created a [word cloud](img/WordCloud.png) for the text from the job descriptions I collected. It seems that "data", "model", "machine learning", and "analysis" are all quite frequent throughout our text and of course, I wouldn't think otherwise. You can also see, very faintly, that data scientist job postings usually want the candidate the know at least Python and SQL.
