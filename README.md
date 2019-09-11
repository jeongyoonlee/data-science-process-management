# Data Science Process Management

This repository compiles resources for data science process management.

It is challenging to establish good process around data science tasks. Many data science tasks end up with one-off solutions that cannot be used in other tasks. Data science tasks don't fit well to either software engineering or product engineering process. Also different data science tasks require different processes.

Yet, it is crucial to have well defined process, because, without it, organizations cannot accumulate knowledge internally, and have to rely on individuals to perform critical tasks. People come and go, while process sticks around.

While there is no good standard so far, there have been active conversations around the issue. 

By compiling those, we hope that it helps us get closer to the best practices in data science process management.

## Understand Data Science Tasks

* [Why Managing Data Scientists Is Different](http://sloanreview.mit.edu/article/why-managing-data-scientists-is-different/) by Roger M. Stein at MIT
* [Big Data – From Descriptive to Prescriptive](http://www.miprofs.com/big-data-descriptive-to-predictive/) by Cameron Cramer
* [The 4 Types of Data Analytics](http://www.kdnuggets.com/2017/07/4-types-data-analytics.html) by Thomas Maydon, Principa
* [Closing the Insights-to-Action Gap](http://www.kdnuggets.com/2017/09/closing-insights-action-gap.html) by Gary Robinson, Lytix.
* [Thoughts on Managing Data Science Team Workstreams](https://medium.com/@HarlanH/thoughts-on-managing-data-science-team-workstreams-and-a-shiny-app-f2b25549946f) by Harlan Harris

## Data Analytics Process

* [What is the Workflow or Process of a Data Scientist](https://www.quora.com/What-is-the-workflow-or-process-of-a-data-scientist/answer/Ryan-Fox-Squire?srid=pJh7) by Ryan Fox Squire on Quora

## Data Science Product Development Process

### Use Cases

* [Meson: Workflow Orchestration for Netflix Recommendations](https://medium.com/netflix-techblog/meson-workflow-orchestration-for-netflix-recommendations-fc932625c1d9) on Netflix Technical Blog
* [Meet Michelangelo: Uber’s Machine Learning Platform](https://eng.uber.com/michelangelo/) on Uber Engineering Blog
* [Bighead: Airbnb’s End-to-End Machine Learning Platform](https://www.slideshare.net/FeiChen29/ml-platform-q1-meetup-airbnbs-endtoend-machine-learning-infrastructure) by Krishna Puttaswamy and Nick Handel
* [Data science at eHarmony: A generalized framework for personalization](https://conferences.oreilly.com/strata/strata-ny-2016/public/schedule/detail/51731) by Jonathan Morra at Strata 2016

### Articles

* [Meet Michelangelo: Uber’s Machine Learning Platform](https://eng.uber.com/michelangelo/) (blog post); also see [scientific paper](http://proceedings.mlr.press/v67/li17a.html) and [talk video](https://youtu.be/MpnszJ_3Ong)
* [Data Science != Software Engineering](https://blog.dominodatalab.com/data-science-software-engineering/) by Domino Data Lab
* [The Practical Guide to Managing Data Science at Scale](https://insidebigdata.com/white-paper/practical-guide-managing-data-science-scale/) by Domino Data Lab
* [Rules of Machine Learning: Best Practices for ML Engineering](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf) by Martin Zinkevich at Google
* [Distributed Time Travel for Feature Generation](https://medium.com/netflix-techblog/distributed-time-travel-for-feature-generation-389cccdd3907) by Hossein Taghavi, Prasanna Padmanabhan, DB Tsai, Faisal Zakaria Siddiqi, and Justin Basilico at Netflix
* [What's Your ML Test Score? A Rubric for ML Production Systems](https://research.google.com/pubs/pub45742.html) by Eric Breck et al. at Reliable Machine Learning in the Wild - NIPS 2016 Workshop
* [Machine Learning: The High Interest Credit Card of Technical Debt](https://research.google.com/pubs/pub43146.html) by D. Sculley et al. at SE4ML - NIPS 2014 Workshop
* [Machine Learning in Production](https://github.com/szilard/ml-prod) by Szilard Pafka at Epoch ([Video](https://www.youtube.com/watch?v=2BTl2maXvFk) at Data Science LA meetup)
* [Insights from a Predictive Model Pipeline Abstraction](https://medium.com/@HarlanH/insights-from-a-predictive-model-pipeline-abstraction-c8b47fd406da) by Harlan Harris
* [Moving Towards Managing AI Products - 10 Lessons for Building AI-Driven Products](https://blog.insightdatascience.com/moving-towards-managing-ai-products-5268c5e9ecf2) by Prasad Velamuri

### Videos

* [Non-Flink Machine Learning on Flink](https://www.youtube.com/watch?v=fZXQZNKFUVE) by Ted Dunning at FlinkForward SF 2017
  > * Work on things that give most return - better data and better questions
  > * Use the decoy (dummy) and canary (baseline/reference) servers
  > * Use the containerized (modular) framework
* [Artificial Intelligence in the Software Engineering Workflow](https://www.safaribooksonline.com/library/view/oreilly-artificial-intelligence/9781491976289/video311928.html) by Peter Norvig at O'Reilly Artificial Intelligence Conference 2017 (subscription required)
* [Machine Learning, Technical Debt, and You](https://youtu.be/V18AsBIHlWs) by D. Sculley at PAPIs 2017
* [Webinar: Managing the Complete Machine Learning Lifecycle](https://pages.databricks.com/201903-US-WB-Managing-the-Complete-Machine-Learning-Lifecycle_ty.html) by Andy Konwinski (Databricks)

### Presentation Slides

* [Production and Beyond](https://www.slideshare.net/turi-inc/model-management) by Rajat Arya and Alice Zheng at Turi
* [10 More Lessons Learned from Building Real-Life Machine Learning Systems](https://chatbotnewsdaily.com/10-more-lessons-learned-from-building-real-life-ml-systems-part-i-b309cafc7b5e) by Xavier Amatriain at Dr.Assist
* [Standardizing the Machine Learning Lifecycle](https://pages.databricks.com/EB-Standardizing-the-Machine-Learning-Lifecycle-LP.html)

## Data Science Knowledge Sharing Process

* [Scaling Knowledge at Airbnb](https://medium.com/airbnb-engineering/scaling-knowledge-at-airbnb-875d73eff091) at AirBnB

## Tools

### Data Analytics Process Templates

* [CRISP-DM](https://en.wikipedia.org/wiki/Cross_Industry_Standard_Process_for_Data_Mining)
  * [Four Problems in Using CRISP-DM and How To Fix Them](http://www.kdnuggets.com/2017/01/four-problems-crisp-dm-fix.html) by James Taylor on [KDnuggets](http://www.kdnuggets.com/)
* [SEMMA](https://en.wikipedia.org/wiki/SEMMA) by SAS
* [Team Data Science Process](https://github.com/Azure/Microsoft-TDSP) by Microsoft
* [Cookiecutter Data Science Template](http://drivendata.github.io/cookiecutter-data-science/) by DrivenData

### Knowledge Sharing

* [knowledge-repo](https://github.com/airbnb/knowledge-repo) by AirBnB

### Data/Modeling/Deployment Pipelines

* [Pachyderm](http://www.pachyderm.io/index.html) - Version control of data and language-agnostic data pipelines
* [Kubernetes](https://kubernetes.io/) - Automating deployment, scaling, and management of containerized applications
* [AWS Data Pipeline](https://aws.amazon.com/datapipeline/) by Amazon - Data pipeline management on AWS
* [Azure Data Factory](https://azure.microsoft.com/en-us/services/data-factory/) by Microsoft - Data pipeline management on Azure
* [AirFlow](https://github.com/apache/incubator-airflow) by AirBnB
* [Oryx](https://github.com/OryxProject/oryx) - Lambda architecture on Apache Spark, Apache Kafka for real-time large scale machine learning
* [Luigi](https://github.com/spotify/luigi) by Spotify
* [MLflow](https://mlflow.org/) by Databricks - an open source platform for managing the end-to-end machine learning lifecycle.
  * [Infrastructure for the Complete ML Lifecycle](https://vimeo.com/274266886#t=33s) by Matei Zaharia at Spark+AI Summit 2018
* [Kubeflow](https://www.kubeflow.org/) - An open-source model training, deployment, and serving tool leveraging the [kubernetes](https://kubernetes.io/) ecosystem.
* [Polyaxon](https://polyaxon.com/) - Another open-source model training, deployment, and serving tool.
* [Algorithmia](https://algorithmia.com/) A SaaS solution for managing the complete ML workflow cycle.
* [Lore](https://github.com/instacart/lore) Framework to structure ML projects and pipelines

### Model Management

* [Steam](https://www.h2o.ai/steam/) by H2O - Model management on H2O
* [Studio](http://studio.ml/) by studio.ml
* [Azure Model Management](https://docs.microsoft.com/en-us/azure/machine-learning/desktop-workbench/deployment-setup-configuration) by Microsoft
* [dotscience](https://dotscience.com/products/)

Open source:

* [ModelDB](https://mitdbg.github.io/modeldb/) by MIT DB Group - Supports Spark ML and Scikit-Learn ([Paper](http://dx.doi.org/10.1145/2939502.2939516))
* [DVC: Version Control System for Machine Learning Projects](https://dvc.org/)

### Experiment Management

* [Comet](https://comet-ml.com/)
* [Weights & Biases](https://www.wandb.com/)
* [Sacred](https://github.com/IDSIA/sacred)