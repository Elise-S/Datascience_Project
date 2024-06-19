# Data Science Project
##  ReadMe of the Data science project by : 

Mina OULHEN, Reyanne ROMAIN, Elise SOENEN

Github page project available at this link : https://github.com/Elise-S/Datascience_Project

#### Requirements 

You will find all the Libraries required in https://github.com/Elise-S/Datascience_Project/blob/main/REQUIREMENTS.txt

Make sure you installed all the libraries before running the notebooks.

For command line: pip install -r requirements.txt

#### Data collection: 

Wikepedia pages were extracted thanks to the web scraper Beautiful Soup.

#### Datasets selected :

- List of women in mathematics. (2024, May 30). In Wikipedia. https://en.wikipedia.org/wiki/List_of_women_in_mathematics

- List of contemporary artists. (2024, May 18). In Wikipedia. https://en.wikipedia.org/wiki/List_of_contemporary_artists

Note that the following abbreviations were used in the code to refer to the different categories:

FM/fm/F_math for the List of women in mathematics

CA/ca/C_art for the List of contemporary artists


#  Part 1 


## Data collection: 

We extract Wikipedia pages for the list of women in mathematics and the list of contemporary artists using four libraries: Wikipedia, SPARQLWrapper, rdflib, BeautifulSoup, and pandas for visualizing our results.

In relation to this part, the folder named Dsprojectrepository contains the following:

- JSON files with the facts and data for both categories

- 2 folders with JSON files for the RDF of both categories

- 2 folders with text files for each category

## Data analysis: 

Using the collected data, we conducted detailed analyses to uncover patterns and differences between the two categories of text. We used different visualizations, such as histograms, box plots, and word clouds, to illustrate these findings on graph and text. Thanks to those visualizations we were able to highlight the characteristics and distinctions of women in mathematics and contemporary artist.

# Part 2 

## Linguistic Comparison 

Using all the collected data obtained in part 1, we were able to compare two linguistic processing libraries, SpaCy and Stanza, on the following three tasks:

- Comparing the performance of Stanza and SpaCy on NER tasks.

- Analyzing the results between Stanza and SpaCy on the types of entities recognized.

- Comparing the named entities recognized by Stanza and SpaCy with the entities in the knowledge graph.

The notebooks are to run in this specific order:
- Part 1:
    - DSproject1_1.ipynb (Data Collection)
    - DSproject1_2.ipynb (Data Analysis)
    - DSproject1_3.ipynb (Clustering)
- Part 2:
    - DSproject2_1.ipynb (NER)
    - DSproject2_2.ipynb (NER Analysis)
    - DSproject2_3.ipynb (NER Verification)



