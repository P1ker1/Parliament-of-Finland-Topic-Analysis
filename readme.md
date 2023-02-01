# Topic Analysis

## Motivation

This is a hobby project of mine which started at the intersection of two things:

* NLP is cool & I wanna learn more!
* We vote, alright, but do we really know what the politicians talk about. There are hours upon hours upon hours of discussions few people follow.
  * As a friend of mine pointed out, there's much more to the duties, e.g. committees, but I have to start somewhere :)

## Technical topics currently touched upon

* Multiple pandas, mainly manipulating dataframes
* Lemmatization using (Voikko)[https://voikko.puimula.org/python.html]
* [Sci-kit learn's TF-IDF vectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html) as the foundation for "quantifying" the text
* Plotting using plt & sns (bars & heatmaps)
  * Not very heavy on analysis
* Dynamic SQL to store results in a local SQLite db in-between the files (especially handy with lemmatized data)
