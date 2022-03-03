## Dataset: Sentiment Analysis of News Articles covering the Olympic legacy of Rio 2016 and London 2012

Add here journal paper

### Statistics about the dataset
To be included

### License
[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode)


### Dataset 1: Sentiment Analysis annotation of News headlines covering the Olympic legacy of Rio 2016 and London 2012 published by the Brazilian and British online media

Dataset of 464 news headlines with sentiment annotated by a domain expert using the labels positive, negative and neutral. Data contains URLs for news articles published between 2004-2020 by the British and Brazilian media in English and Brazilian Portuguese covering the Olympic legacies of London 2012 and Rio 2016. Articles were collected from the news outlets’ websites using Google search engine.

#### News outlets:

- The Guardian
- Daily Mail
- Globo
- Estadao

#### Events covered by the articles:

- London 2012 Olympic legacy
- Rio 2016 Olympic legacy

#### Language of news headlines:

- English
- Portuguese (Brazil)

#### The documents are composed of the following columns:

- Rank: the position of the article on Google search ranking
- Date: date of article's publication (DD/MM/YYYY)
- Link: article's link
- Title: article's title
- Labels: sentiment label assigned manually to each news headline

#### Sentiment is presented in labels as follows:

- Positive
- Negative
- Neutral

#### Citation
*Mello, C. & Cheema, G. (2022). Dataset: Sentiment Analysis annotation of News headlines covering the Olympic legacy of Rio 2016 and London 2012 published by the Brazilian and British online media [Data set]. Zenodo. https://doi.org/10.5281/zenodo.6323964*

### Hosted on Zenodo
https://zenodo.org/record/6323964#.Yh_UdXXP3RZ

### Dataset 2: Sentiment Analysis annotation of News headlines covering the Olympic legacy of Rio 2016 and London 2012 published by the Brazilian and British online media

Sentiment Analysis outputs based on the combination of three classifiers for news headlines and body text covering the Olympic legacy of Rio 2016 and London 2012. Data was searched via Google search engine. It is composed of sentiment labels assigned to 1271 news articles in total.

#### News outlets:
- BBC
- Daily Mail
- The Telegraph
- The Guardian
- Globo
- Estadao
- Folha de S. Paulo

#### Events covered by the articles:

- London 2012 Olympic legacy
- Rio 2016 Olympic legacy

All classifiers were used in texts in English. Text originally published in Portuguese by the Brazilian media were automatically translated.

#### Sentiment classifiers used:

- Vader
- BERT (Trained on Amazon data)
- BERT (Trained on twitter data - 140)

Each document (spreadsheet - xlsx) refers to one outlet and one event (London 2012 or Rio 2016).

#### How were labels assigned to the texts?

These labels are a combination of the three sentiment classifiers listed above. If two of them agree with the same label, then this label would be considered as right. Otherwise, the label ‘other’ was assigned.

For news article body text: the proportion of sentences of each sentiment type was used to assign labels to the whole article instead of averaging the sentence scores. For example, if the proportion of sentences with negative labels is greater than 50%, then the article is assigned a negative label.

#### The documents are composed of the following columns:

- Rank: the position of the article on Google search ranking
- Date: date of article's publication (DD/MM/YYYY)
- Link: article's link
- Title: article's title
- Sentiment_Title: final sentiment for article headline
- Sentiment_Text: final sentiment for article's body text

PS: Documents do not include articles' body text.

#### Sentiment is presented in labels as follows:

- Pos: Positive
- Neg: Negative
- Neutral: Neutral
- other: inconclusive - if each of the 3 classifiers assigned a different label to the article, the label 'other' was used. Therefore, 'other' identifies contradictory results.

#### Citation
*Mello, C. & Cheema, G. (2022). Sentiment Analysis outputs based on the combination of three classifiers for news headlines and body text [Data set]. Zenodo. https://doi.org/10.5281/zenodo.6326348*

### Hosted on Zenodo
https://zenodo.org/record/6326348#.YiEuq9vLfRZ

