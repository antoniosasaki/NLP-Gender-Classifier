## A gender prediction study from census manuscript data
**By Antonio Sasaki**

The Socface project brings together researchers to analyze French census records from 1836 to 1936. They are using advanced technology to extract information from handwritten lists, but in certain censuses gender information may be missing. Thus, as this is essential for other analyses, our objective in this work is to use machine learning knowledge to develop a **gender prediction model** based on available data.

### Appendix 1: Explaining what you will find in this repository
In the **French census data** folder you will find the two CSV files that were used in this work. The main results present in the report are contained in **Classifier (with probability)** as I am also considering the CSV file with the gender distribution for each name. In the data from the main file, with the transcriptions, there are male, female and ambiguous genders. Therefore, there are three different types of genders that we will try to predict with our model. The **Classifier (without probability)** was just a draft in which we studied the same results but without considering the second CSV file.

### Appendix 2: the meaning of ’ambigu’ in the data frame
It is also possible to understand the meaning of ’ambigu’, that appears in the gender column, not
signifying non-binary gender (as we assumed) but rather imprecision from the census collector in defining the individual’s
gender. In this case, we could discard this information and would have a prediction model with only two
genders, which would be much more straightforward. It is highly likely that this type of model would
be entirely based on the probability estimator, and its scoring and accuracy measures would easily reach
100%.

