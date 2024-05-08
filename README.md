## A gender prediction study from census manuscript data
The Socface project brings together researchers to analyze French census records from 1836 to 1936.
They are using advanced technology to extract information from handwritten lists, but in certain censuses
gender information may be missing. Thus, as this is essential for other analyses, our objective in this work
is to use machine learning knowledge to develop a gender prediction model based on available data.

### Appendix 1: the meaning of ’ambigu’ in the data frame
It is also possible to understand the meaning of ’ambigu’, that appears in the gender column, not
signifying non-binary gender but rather imprecision from the census collector in defining the individual’s
gender. In this case, we could discard this information and would have a prediction model with only two
genders, which would be much more straightforward. In this case, it is highly likely that the model would
be entirely based on the probability estimator, and its scoring and accuracy measures would easily reach
100%. For these reasons, it is more challenging to interpret these data as motivating the existence of a
third gender that can be understood and identified by our classifier, which was the scenario we assumed.

