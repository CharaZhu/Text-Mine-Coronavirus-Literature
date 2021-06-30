# Text Mine COVID-19 Literature

#### Apply NLP and ML algorithms on over 400,000 biomedical research papers to gain insight into COVID-19 and how to improve vaccination efforts.
</br>


#### TABLE OF CONTENTS 
- [Background](#background) 
- [Dataset](#dataset) 
- [Requirement](#requirement)
- [Technical Approach](#Technical-Approach)
- [Limitations and Future Improvements](#Limitations-and-Future-Improvements)
<br/>

 
## Background
In response to the COVID-19 pandemic, the White House and a coalition of leading research groups have prepared a dataset of open sourced research papers. This data set is a resource of over 400,000 scholarly articles, including over 150,000 with full text, about COVID-19. This freely available dataset is provided to the global research community to apply recent advances in natural language processing and other AI techniques to generate new insights in support of the ongoing fight against this infectious disease. There is a growing urgency for these approaches because of the rapid acceleration in new coronavirus literature, making it difficult for the medical research community to keep up and extract insights from this growing body work. 

The goal of this project is to use NLP and other machine learning algorithms to develop a tool that can text-mine this database of research articles to gain useful insights about COVID-19 and how we might be able to tackle the outbreak, contain the spread, flatten the curve and improve vaccination efforts. The overarching insights that can be acquired from this dataset are numerous and which aspect of the problem you decide to tackle is up to you. For example you may choose to use this dataset to better understand the transmission, incubation and symptoms of COVID-19, look to gain insights around which therapeutics and vaccines may hold promise and warrant further investigation, or you may wish to investigate the risk factors that make COVID-19 particularly deadly in some patients. The underlying goal of this project is to gain insights from this dataset to better inform how our healthcare system, governments, industries can tackle this growing problem.

</br>  


## Dataset

- metadata.csv: a corpus of published research articles and corresponding metadata on findings about the corona virus. Paper abstracts are found directly in the file whereas the full text for the papers can be acquired using the links provided within.

- .json files containing the full texts for papers in the above dataset can be downloaded from here: https://bit.ly/3fzhlhD

</br>   
 
 
## Requirement
numpy, Scipy, Scikit, Matplotlib, Pandas, NLTK
</br> </br>
 
 
 
## Technical-Approach

#### 1. Data Cleaning 
- Remove duplicate papers  
- Extracting useful fields (authors, abstracts, date of publication ...)
- Prepares the data for analysis (remove stop words, lematization ...)

#### 2. Data Visualization and Exploratory Data Analysis 

#### 3. Model selection and fitting to data  
 
#### 4. Deriving insights   
- Policy and action to tackle the outbreak  
</br> </br>
 
 
## Limitations and Future Improvements

* Add more explanations (Requirement) 
 

 
 
