# Vectorization

# Introduction

![alt text](https://th.bing.com/th/id/R.a1293480c0ed6bf1ff72d05fe29192f7?rik=DVw9%2bCEtr%2bP0zw&riu=http%3a%2f%2fgifimage.net%2fwp-content%2fuploads%2f2017%2f11%2fintroduction-gif-7.gif&ehk=fIq34BcPvQ7sY2qaVQQHd8qRyH%2bQc7gVgyBiq9zbFx4%3d&risl=&pid=ImgRaw&r=0)

In Natural Language Processing (NLP), vectorization pertains to transforming textual information into numerical vectors that can serve as machine learning model inputs. Essentially, it involves converting text into a numeric format that algorithms can handle.

Vectorization plays a crucial role in NLP as machine learning models generally operate on numerical input data. Through converting text into a vectorized format, we can employ a diverse set of numerical methods to analyze and manipulate language data.

# What has been performed

Two types of vectors have been applied to this dataset: count vectors and TF-IDF vectors. The purpose of using both these techniques was to highlight the contrast between them. To enhance understanding, a theoretical explanation has been provided below.

# Types of vectors

1. The count vector approach involves representing a document as a vector based on the frequency of each word in the document. This results in a vector with higher values for frequently occurring words and lower values for rarely or non-occurring words.

2. In contrast, the TF-IDF vector approach represents a document as a vector of weighted word counts that takes into account the frequency of each word in the entire corpus of documents. Words that occur frequently across the corpus are given a lower weight, while words that are rare in the corpus are given a higher weight.

# Conclusion

To put it concisely, count vectors depict documents in the form of a word count vector, whereas TF-IDF vectors portray documents as a weighted word count vector, which factors in the significance of each word in the corpus as a whole.