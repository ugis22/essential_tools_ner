# The essential tools for Named Entities Recognition

Read more about this project on [Medium](https://towardsdatascience.com/discovering-the-essential-tools-for-named-entities-recognition-8176c94d9747).

## Introduction

It is easy for us to put words under categories. We can tell which word is a noun, an adjective or a verb in a text. We can point out the name of a person, an organization or a country.

This is not an easy task for a machine. However, we have come a long way.

Now, we don't need to spend long hours reading long texts anymore. We can use machine learning algorithms to extract useful information such as names from them. These names, known as entities, are often represented by proper names. They share common semantic properties. And they usually appear in similar contexts.

We use words to communicate with each other. We tell stories. We state our thoughts. We communicate our feelings. We claim what we like, dislike or need. Nowadays, we mostly deliver things through written text. We tweet. We write in a blog. The news appears on a website. So written words are a powerful tool.

If we can recognize which people, organizations, companies, brands or locations are mentioned in different news, tweet or post in the web, we could detect and assign relevant tags for each article or post. This will help us distribute them in defined categories. We could match them specifically with the people that are interested in reading about that type of entities. Using the keywords, we would also be capable of recommending articles, websites or post very efficiently. 

We can also recommend products or brands. If someone complains about a particular brand or product, we can easily assign it to the most idoneous department in a matter of seconds. 

NER is a very useful tool. 

## Purpose

The aim of this repository is to show the different tools along with the use of pre-trained models that can be used for Named entities recognition.

## Content 

The repository contains the following files:

- `essential_tools_ner.ipynb`
- `requirements.txt`

## Tools used

- `BeautifulSoup`
- `requests`
- `NTLK`:
  - `word_tokenize`
  - `pos_tag`
- `Spacy`
