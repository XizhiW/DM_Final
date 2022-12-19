{README template}

# Project title (2022 Fall ADM)
{Movie Recommendation using Graph Embedding with DeepWalk and Node2Vec}

* Team (members): Xizhi Wu (email) xiw183@pitt.edu
* Project presentation: click [here](DM_Final_Presentation.pdf) to visit presentation slides
* Project paper: click [here](Final_Report.docx.pdf) to visit final report


{Readme}

## Description
{In this project, we show how deepwalk and node2vec can be used to generate movie recommendations by learning user-movie graph embedding.}
* DM_Final_Presentation.pdf: A presentation slide for this project
* Create Final_Netflix_Movie_Recommendation.ipynb: Code
* Final_Netflix_Movie_Recommendation.pdf: A pdf of the colab notebook
* Final_Report.docx.pdf: Project report
* License: License
* Readme: Readme

## Prerequisites
{This project if being run on Google Colab.
If you are using Colab, you will install: !pip install stellargraph
else on a personal notebook, make sure you install any version of the following library: 
matplotlib
math
sklearn
networkx
numpy
pandas
stellargraph
collections
multiprocessing}

## Authors
{Xizhi Wu, xiw183@pitt.edu}

## Acknowledgments
{I would like to thank Dr. Lin for answering my questions and giving me guidance implementing my ideas. 
I would also like to thank my friends Auru and Yijun for providing answers and reflection on my questions and readings.}

## License
{click [here](License) to see License}
[MIT](https://choosealicense.com/licenses/mit/)

------------------------------

## Project requirement 

In this homework assignment, you will extend your hw01 and hw02. Your goal is to incorporate two different graph-based neural network methods to boost the recommendation performance. You will test your new implementation using the same Netflix Prize data.

1. We have covered several graph-based neural network methods in our class and readings, including shallow and deep approaches, knowledge graph appraoches, etc. Pick **two distinctive methods** that you are interested in, implement and evaluate their performance on the Netflix movie recommendation dataset. In your final report, explain why you select the methods, and provide a rationale for why you think the method may potentially improve your recommender system.
2. Use the best two models from your previous assignments (hw01, hw02) as your baseline.
    * (B1) your best model from hw01-02; describe what the model is
    * (B2) your 2nd best model from hw01-02; describe what the model is
    * (A1) your first graph-based neural network model
    * (A2) your first graph-based neural network model

3. Compare the model performance based on both implicit and explicit feedback. This allows you to understand the strength of your models. For explicit feedback, use MAPE and RMSE as evaluation metrics (as in hw01), and for implicit feedback, use HR and NDCG (as in hw02). In your final report, provide a detailed performance analysis and discuss the strengths and weaknesses of your models.

**Note:**  If you use anyone's shared code or build your model based on any existing repositories, make sure you include all of them in your acknowledgment and references.

4. Your submission will include (1) a reproducible notebook, (2) project presentation slides, and (3) a final paper. See [final project guideline](https://drive.google.com/file/d/1OFsUgGk7FOYi8qJ4fv7_4J5IA-bRMsU_/view?usp=share_link) for more details.
