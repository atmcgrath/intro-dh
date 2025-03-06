---
title: Text Analysis
date: March 6, 2025
author: Alice McGrath
output:
    revealjs::revealjs_presentation:
    reveal_option:
slideNumber: true
css: "https://alicemcgrath.digital.brynmawr.edu/pres/a3.css"
---

## Agenda
1. Final project proposal questions
2. Text analysis examples
3. Cultural analytics tutorial

---

## Project proposal questions

[Project Proposal instructions](https://moodle.brynmawr.edu/mod/assign/view.php?id=370332)

---

## Text Analysis Methods

![A google N-gram showing War and Peace](https://alicemcgrath.digital.brynmawr.edu/pres/media/ngram-war-peace.png)
<small>From the [Google Books NGram viewer](https://books.google.com/ngrams/)</small>

--- 

## Natural Language Processing

- Bag-of-words: word counts, regardless of word order
- Language models: machine learning algorithms trained on language-specific datasets

---

## Word counting

<section>

### Methods

- N-gram frequency (unigrams, bigrams, trigrams)
- KWIC: Keywords in context/concordance
- Collocations: words that appear in close proximity
- Topic modeling: sets of words that appear together across multiple documents
- TF-IDF: term-frequency inverse-document-frequency

</section>
<section>

### Examples

- [Fan Engagement Meter](https://fanengagement.org/) - Peter Decherney, James Fiumara, Scott Enderle (Price Lab) - quantifying text reuse in fan fiction archives from popular film franchises
- [On The Books](https://onthebooks.lib.unc.edu/) - UNC - identifying Jim Crow laws that have not been repealed

</section>

---

## Language models

<section>

### Methods 

- Named Entity Recognition/parts-of-speech tagging
- Word vectors/word embeddings
- Sentiment analysis*
- Text classification
- Text prediction/generation

</section>
<section>

### Examples

- [Sentiment analysis of Weimar film reviews](https://culturalanalytics.org/article/118497), Campregher Paiva & Diecke
- [Stanford Lit Lab: Domestic Spaces in Fiction](https://litlab.stanford.edu/projects/domestic-space/)

</section>

--- 

## TF-IDF

<section>

[TF-IDF with SciKit Learn](https://melaniewalsh.github.io/Intro-Cultural-Analytics/05-Text-Analysis/03-TF-IDF-Scikit-Learn.html), from *Intro to Cultural Analytics in Python*.

</section>
<section>

- Access the notebook from your [Python Github Classroom assignment](https://github.com/Bryn-Mawr-College/hist-105b-intro-python-intro-python/tree/main)
- Merge pull request
- Download to your desktop or open in CodeSpaces

</section>
<section>

## Other resources

[Constellate tutorial on Significant Terms](https://constellate.org/tutorials/no-code/significant-terms)

</section>

---

## Tools and resources

- [Voyant-tools.org](https://voyant-tools.org/) - no-code corpus exploration
- [Constellate](https://constellate.org/) no-code tutorials and jupyter notebook tutorials for a range of methods