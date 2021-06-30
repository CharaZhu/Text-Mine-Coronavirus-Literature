# COVID-19 pandemic

##### use NLP and ML algorithm on the database of research articles to gain useful insight about COVID-19 and how to improve vaccination efforts.

</br>


#### TABLE OF CONTENTS 
- [Background](#background) 
- [Dataset](#dataset) 
- [Requirement](#requirement)
- [Technical Approach](#Technical-Approach)
- [Limitations and Future Improvements](#Limitations-and-Future-Improvements)
- [Reference](#Reference)  
<br/>

 
## Background
In response to the COVID-19 pandemic, the White House and a coalition of leading research groups have prepared a dataset of open sourced research papers. This data set is a resource of over 400,000 scholarly articles, including over 150,000 with full text, about COVID-19. This freely available dataset is provided to the global research community to apply recent advances in natural language processing and other AI techniques to generate new insights in support of the ongoing fight against this infectious disease. There is a growing urgency for these approaches because of the rapid acceleration in new coronavirus literature, making it difficult for the medical research community to keep up and extract insights from this growing body work. 

The goal of this project is to use NLP and other machine learning algorithms learned in this course to develop a tool that can text-mine this database of research articles to gain useful insights about COVID-19 and how we might be able to tackle the outbreak, contain the spread, flatten the curve and improve vaccination efforts. The overarching insights that can be acquired from this dataset are numerous and which aspect of the problem you decide to tackle is up to you. For example you may choose to use this dataset to better understand the transmission, incubation and symptoms of COVID-19, look to gain insights around which therapeutics and vaccines may hold promise and warrant further investigation, or you may wish to investigate the risk factors that make COVID-19 particularly deadly in some patients. The underlying goal of this project is to gain insights from this dataset to better inform how our healthcare system, governments, industries can tackle this growing problem.

</br> </br> 


## Dataset

- metadata.csv: a corpus of published research articles and corresponding metadata on findings about the corona virus. Paper abstracts are found directly in the file whereas the full text for the papers can be acquired using the links provided within.
- .json files containing the full texts for papers in the above dataset can be downloaded from here: https://bit.ly/3fzhlhD

</br> </br>  
 
 
## Requirement
numpy, Scipy, Scikit, Matplotlib, Pandas, NLTK
</br> </br> 
 
 
## Technical-Approach

#### 1. Data Cleaning 

cleans the data by removing duplicate papers, making the text contents easier to mine by adjusting formatting, and extracting useful fields from the larger dataset such as authors, abstracts, date of publication and more.  


</br> </br> 

#### 2. Data Visualization and Exploratory Data Analysis
Depending on your overarching theme and questions that you wish to address about COVID-19 present 3 graphical figures that visualize aspects or information in the data that you will further explore with your models. How could these trends be used to help with the task of methodically extracting all information and trends of this type? Consider how accessing the data and creating these visualizations will inform how the data will need to be pre-processed and fed into your models. All graphs should be readable and presented in the notebook. All axes must be appropriately labeled. In addition to data visualizations, perform exploratory data analysis in other forms, if necessary.
</br> </br> 

#### 3. Model selection and fitting to data 
Select a machine learning model of your choice (you may select an unsupervised or supervised machine learning model depending on your approach) that will allow you to study some aspect of COVID-19 from the corpus of research articles. You must justify your algorithm choices and the approach you will use to fit your model using the dataset provided. You may also choose to study multiple models and report on the suitability of each in addressing your overarching question regarding COVID-19. You should also use the dataset provided to train the models selected and discuss and interpret the findings of these models. You may also use this section to improve the model depending on the findings of your models and how you interpret them.
</br> </br>


#### 4. Deriving insights about policy and guidance to tackle the outbreak based on model findings 
Using the findings from your NLP model and text mining 400,000 unique biomedical research papers on the coronavirus you are now tasked with discussing and proposing how scientists, doctors, nurses, healthcare professionals, industry and governments can best use the insights from your data science model to assist in the fight against the COVID-19 pandemic. Use the insights derived about the disease from your model and your data analysis to justify proposed policies or action items.
</br> </br>
 
 
## Limitations and Future Improvements
...

* Add more explanations (Requirement, algorithm) 
 

 
 
