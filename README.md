# Poems-Classification

Data Source: https://www.kaggle.com/ultrajack/modern-renaissance-poetry

Poems from poetryfoundation.org dataset consists of poems from different genres.

Number of poems : 573

Number of Attributes/Columns in data : 5

### Attribute Information:

1. author - author name
2. content - poem content
3. poem name
4. Age - poetry style era
5. type - category/genre 

### Objective:

Given a poem, determine whether the genre that poem belong to.

## WORK FLOW
1. Text Preprocessing
2. Converted Text to Vectors using :
   a. Bag of Words
   b. TF-IDF
   c. Avg-W2V
3. Applied Naive Bayes after all vectorization techniques to find the best model
4. Applied Logistic Regression after all vectorization techniques to find the best model

