# Natural Language Processing

This repo comprises of several projects completed for the Natural Language Processing course at IE University's MS in Business Analytics and Big Data program.

## Topic Modelling: Domestic Violence Application

Domestic Violence is not a pandemic, it’s an epidemic. With Covid-19 ravaging the economy and increasing unemployment; such crises are set to become much more frequent. Add another public health crisis to the toll of the new coronavirus: Mounting data suggests that domestic abuse is acting as an opportunistic infection, flourishing in the conditions created by the pandemic.

With topic modelling, we were looking to identify the different topics or classes of the tweets or comments in Reddit  to make the large and unstructured data more organized in a way that will make it easier for NGOs, government officials or researchers to assess and get useful insights from to better analyze this crisis and come up with better courses of action.

Reddit comments (+- 1200) and tweets (+- 25 000) were scraped with searches or hashtags **#METOO, #WHYISTAYED, #WHYILEFT,#HeForSheAtHome, #WomenCount, #GenerationEquality,
#AntiDomesticViolenceDuringEpidemic, #Mask-19, #WithHer, #SpotlightEndViolence** and **#staysafe**. 

Three topic modelling techniques were applied:

 - Latent Semantic Indexing (LSI)
 - Hierachical Dirichlet Process (HDP)
 - Latent Dirichlet Allocation (LDA) 

The topics were identified across five countries where the conversation of Domestic Violence was most prominent; namely USA, UK, India, Nigeria & Kenya.
 
An in-depth report reviewing relevant literature, outlining the methodology taken and summarizing insights made, is available [here](https://github.com/maz2198/Natural-Language-Processing/blob/master/DomesticViolenceTopicModelling/NLPAssignment_GroupA/Final%20Report_GroupA.pdf). The final website and application can be viewed at [Domestic Violence: Topic Modelling](https://bfdelavega.wixsite.com/misitio).

This project was completed with my colleagues Adelina Akhsanova, Nisrine Ferahi, Begona Frigolet, Mohamed Amer and Prasanth Chakka.

## Real or Not: Tweets Disaster Classification

The main objective of this project wass to classify these tweets on whether they are about real disasters or not.

We are given a dataset of almost 11,000 tweets and can be downloaded [here](https://www.kaggle.com/c/nlp-getting-started/overview).
The complication comes because many tweets have words that would imply a disaster but are used metaphorically. Therefore, merely identifying the presence of such words would not guarantee that the tweet is in fact referring to an actual disaster. We have just three pieces of information to do this, 
- the tweet
- the key word in the tweet 
- location of tweet account.

Several preprocessing techniques and the use of n-grams, lemmatization, stemming and different tokenizers were applied. Moreover, an ensembled voting classifier consisting of a Logistic Regression Model, Multinomial Naive-Bayes and SVM. The entire preprocessing and modelling is outlined in `NLP_MarangMutloatse.ipynb`. An summary of the methodology, results and insights are outlined in `NLP_Report.pdf`

