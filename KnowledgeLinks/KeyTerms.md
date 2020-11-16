# Natural Language Processing (NLP)

NLP is abbreviation of Natural Language Processing, concerns itself with the interaction between
natural human languages and computing devices, NLP is a major aspect of computational linguistics.

There are some important notes about that:

## Tokenization:
  Tokenization is really important level of NLP, because in this step we split longer String text into 
  smaller String text. Larger chunks of text can be tokenized into sentences, sentences can tokenized into words and etc...

## Normalization 
  Before any processing, text needs to be normalized, in NLP normalization has unique    explanation, Normalization describe series of related tasks meant to pull all text on a level playing field, that's mean converting all text to UPPER or lowe case or removing some punctuation or converting numbers to their words and so on. Normalization puts all words on equal footing, and allows processing to proceed uniformly.
  
  ## Stemming
   Stemming is the process of removing some affixes and suffixed (prefixes, infixes, circumfixes) from words in order to obtain a word stem (داشتن ریشه کلمه).
   reading into read or in Persian Language (if you want learn more about that click on below link)
   
[stemming of words](https://fa.wikipedia.org/wiki/%D8%B1%DB%8C%D8%B4%D9%87_(%D8%B2%D8%A8%D8%A7%D9%86%E2%80%8C%D8%B4%D9%86%D8%A7%D8%B3%DB%8C))

  ## Lemmatization
  For this section i haven't any explan (for now) but...
  
  For example, stemming the word of better would fail to return its citation form another word for lemma. better convert to good
  
  ## Corpus
  In linguistics and NLP, corpus (literally Latin for body) refers to a collection of texts. Such collections may be formed of a single language of texts, or can span multiple languages -- there are numerous reasons for which multilingual corpora (the plural of corpus) may be useful. Corpora may also consist of themed texts (historical, Biblical, etc.). Corpora are generally solely used for statistical linguistic analysis and hypothesis testing.
  
  ## Parts of speech (PoS) Tagging
  PoS tagging consists of assigning a category tag the tokenized parts of a sentences.  
  The most popular PoS tagging would be identifying words as nouns, verbs, adj and etc...
  
  
  ## Statistical Language Modeling
  Statistical Language Model is the process of building a statistical language model which is meant to provide an estimate of a natural language. For a sequence of input words,  the model would assign a probability to the entire sequence, which contributes to the estimated likelihood of various possible sequences. This can be especially useful for NLP applications which generate text.


  ##  Bag of Words
  Bag of words is a particular representation model used to simplify the contents of a selection of text. The bag of words model omits grammar and word order, but is interested in the number of occurrences of words within the text. The ultimate representation of the text selection is that of a bag of words (bag referring to the set theory concept of multisets, which differ from simple sets).
  
"Well, well, well," said John

"There, there," said James. "There, there."

The resulting bag of words representation as a dictionary:

    {
      'well': 3,
      
      'said': 2,
      
      'john': 1,
      
      'there': 4,
      
      'james': 1
      }
      

## n-grams 
n-grams is another representation model for simplifying text selection contents. As opposed to the orderless representation of bag of words, n-grams modeling is interested in preserving contiguous sequences of N items from the text selection.

In simpler terms, that use sequece of sentences and change place of words together.
  
"Well, well, well," said John

"There, there," said James. "There, there."

    [
      "there there said",
      
      "there said james",
      
      "said james there",
      
      "james there there",
    ]
