---
title: Analyse
topics: Processing methods; NLP; Common tasks; Useful tools; Useful platforms; Codings
nav: true
---

# Data analysis
Data analysis takes on many names and may forms.  In the context of this resource data analysis is the use of code or tools to process the data we have collected, cleaned and formated for use. 
This is where we use our data to inform our decision making, identify themes and gaps in the research and find evidence to support findings. 


## Methods for analysis

Once the text is cleaned and formatted it can be computationally processed using a number of different methods, depending the analysis you want to undertake. Explore some of popular the methods below. 

### Natural language processing (NLP) techniques

Natural language processing (NLP) is the branch of artificial intelligence (AI) technology to train a computer to understand, process, and generate language. Search engines, machine translation services, and voice assistants are all powered by the technology. Source: [Bell & Olavsrud, 2021](https://www.cio.com/article/228501/natural-language-processing-nlp-explained)

The following NLP tasks break down text into analysable parts:

| NLP method | Description | Example |
| Tokenization |Splits the text into sentences and sentences into words; changes to lowercase and removes punctuation. | This is creates a 'bag of words' for analysis |
| Stop word removal | Uses standard language stop word dictionaries which can be amended. | removes words such as "the", "and", "it", "so", "this", "page", "of".... |
| Lemmatization | Third person words are changed to first person and verbs in past and future tenses are change into present. | Alters change, changing, changes, changed... to change |
| Word stemming | Words are reduced to their root form. | Changes victorious, victories, victory... to victor |
| Special characters removed | Characters that cannot be understood are removed. | * @ # ! >> |
| Part-of-speech tagging | Categorises words in a text in correspondence with a particular part of speech. | Her `(pronoun)` hat `(noun)` is `(verb)` grey `(adjective)`. |
| Shallow parsing | Chunks phrases from unstructured text. | Identifies sentences, verb phrases, noun phrases. |
| Syntactic parsing | Finds structural relationships between words in a sentence. | Can for example identify a noun phrase as being formed by a determiner, followed by an adjective, followed by a noun. |
{:.table .table-bordered}

{% include figure.html img="BagOfWords.PNG" alt="Bag of words" caption="Natural Language Processing - tokenization" width="100%" %}

### Machine learning
Machine learning is a branch of AI and a process of teaching a computer system to recognise patterns in text without explicit human programming. Machine learning can be either unsupervised (with minimal human intervention) or supervised (with more human intervention). Explore machine learning at [Zdnet.com](https://www.zdnet.com/article/what-is-machine-learning-everything-you-need-to-know/). Analysis using Machine learning includes topic modelling, and Naive Bayes Classification, which are detailed below.


# Common computational analysis tasks

Explore some common computational text analysis methods. 

{% include figure.html img="TextAnalysisTasks.png" alt="Text analysis tasks" caption="Text analysis tasks" width="100%" %}

### Text pattern analysis

| Linguistic patterns | such as word frequency analysis is useful for historical exploration of language as well as topic identification |
| Collocation | identifies words commonly appearing near each other |
| Concordance | shows the context of (the words around) a given word or set of words |
| N-grams | finds common two-, three-, etc. word phrases see [Google books Ngram viewer](https://books.google.com/ngrams/) |
| Dictionary tagging | locates a specific set of words in texts |
{:.table .table-bordered}

### Analysing one or a number of texts of interest

| Method | Description | Example |
| Topic modeling | Unsupervised machine learning to identify groups of terms that may be representative of a given topic, uncovering hidden themes. | [Topic mapping for a literature review](https://doi.org/10.1111/faf.12399) |
| Document classification | Such as Naive Bayes Classfication uses machine learning to classify documents based on information in the text | Used in Sentiment analysis and [literature reviews](https://doi.org/10.1016/j.ins.2020.03.006). |
| Sentiment analysis | Used to determine whether text is positive, negative, or neutral. Used in research to see public sentiment, opinions, or emotions about products, ideas or policy, and can undertaken via NLP or machine learning. | [Tweet Sentiment Visualization App](https://www.csc2.ncsu.edu/faculty/healey/tweet_viz/tweet_app/) from NC State University. | 
| Network analysis | Analysis of social or other structures comprising variables or actors (represented by nodes), and the relationships (edges) between the nodes | [Network Analysis 101](https://cphss.wustl.edu/methodsandstrategies/social-network-analysis/network-analysis-101/) |
| Named entity recognition | Generates a list of people, places, dates, times etc. | [Booking.com user experience analysis](https://booking.ai/named-entity-classification-d14d857cb0d5)|
| Stylometry | Statistical method of studying a linguistic style. | Used in [forensic](https://ieeexplore.ieee.org/abstract/document/9107953), [attribution](https://doi.org/10.12697/smp.2018.5.2.02) and [genre](https://doi.org/10.1093/llc/fqac019) analysis. |
{:.table .table-bordered}

Learn more about these methods from:
- [Australian Text Analytics Platform Methods Guide](https://www.atap.edu.au/text-analysis/methods/)
- [An Introduction to Text Mining: Research Design, Data Collection, and Analysis ebook](https://methods.sagepub.com/book/an-introduction-to-text-mining/i1237.xml)
- Prof. Miriam Possner's [Topic Modelling online tutorials](http://miriamposner.com/classes/dh201w21/tutorials-guides/text-analysis/messing-around-with-the-topic-modeling-tool/)
- [Demystifying Networks](http://www.scottbot.net/HIAL/index.html@p=6279.html) an introduction for HASS scholars.
- [Introduction to Sentiment analysis](https://www.youtube.com/watch?v=i4D5DZ5ZG-0) fun and informative video.
- [Article on comparison of machine learning methods for text-based sentiment analysis](https://doi.org/10.1016/j.ijresmar.2021.10.011)
- [Article by Berger et al. on text analysis methods used in Marketing](https://doi.org/10.1177/0022242919873106)

{% capture text %}
After applying these compuational processing and analysis models and methods, the data will be ready for the most important and interesting stage, your analysis and interpretation of the results. {% endcapture %}{% include alert.html text=text color="info" %} 

----
##  Analysis tools

{% capture text %}
- [NVivo](https://www.griffith.edu.au/student-computing/available-software) : performs cluster analysis, phrase nets, tag clouds, and sentiment analysis. 
- [Leximancer](https://www.griffith.edu.au/student-computing/available-software) : performs network analysis, topic modeling, sentiment analysis, and named entity recognition.

Login and installation are required for both. Training is available for Griffith researchers via [Researcher Education & Development](https://www.griffith.edu.au/research/research-services/researcher-education-development/workshop-calendar).{% endcapture %}{% include card.html header="Griffith University subscription software" text=text %}

{% capture text %}
The virtual research environments below have been developed to support digital text scholarship.
- [JSTOR text mining support](https://about-jstor-org.libraryproxy.griffith.edu.au/whats-in-jstor/text-mining-support/) :  for metadata, n-grams, and word counts for most articles and book chapters, and for all research reports and pamphlets available via Griffith University's subscription to JSTOR. Login required.
- [Gale Digital Scholar Lab](http://libraryproxy.griffith.edu.au/login?url=https://infotrac.gale.com/itweb/griffith?db=DSLAB) : for document clustering, named entity recognition, Ngrams, Parts of Speech, Sentiment Analysis, Topic Modelling all available via Griffith University's subscription. The lab is designed to use the Gale Primary Source archives, but you can use the analysis tools with your own data. Learn about it and Gale Primary Sources [here](https://sway.office.com/v4sYacFkErbH9HNo). Includes [online tutorials](https://go-gale-com.libraryproxy.griffith.edu.au/ps/helpCenter?userGroupName=griffith&inPS=true&nspage=true&prodId=DSLAB&docId=VJWVZS717322017). Login required. 
- [Hathi Trust Research Center Analytics](https://analytics.hathitrust.org/) : supports large-scale computational analysis of the digital library works to facilitate non-profit and educational research. Individual researchers can sign up for free with their Griffith email and use out of copyright materials and analysis tools.  
- [Proquest TDM Studio](https://tdmstudio.proquest.com/) : create an account with your university email address.  Undertake geographic analysis, topic modelling or sentiment analysis of Proquest's collection of newspapers, dissertations and theses. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/etRaylzA6AE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
{% endcapture %}{% include card.html header="Platforms with prepared text and tools" text=text %}

{% capture text %}
The tools listed below enable users to undertake text analysis without the need to learn to code. The majority of the tools are based on Python or R codes. You can use these tools for simple or exploratory data analysis and some visulations. Some tools are downloadable to your computer, others are web interfaces, each with their own benefits and limitations.

| Advantages | Disadvantages |
| Easier to learn than coding, good for high level analysis | Can be inflexible, may not be good for deeper analysis, web based tools may not approprate for using with identifiable data. |
{:.table .table-bordered}

- [Voyant Tools](https://voyant-tools.org/) web based online tool for frequency, distribution and collocation of terms, keywords in context, term clusters and more.
- [Sentiment Analyzer](https://www.danielsoper.com/sentimentanalysis/default.aspx) web based tool for analysing one source at a time.
- [Topic Modelling tool](https://senderle.github.io/topic-modeling-tool/documentation/2017/01/06/quickstart.html)a GUI for MALLET modelling code.
- [Cytoscape](https://cytoscape.org/) software platform for visualizing complex networks. 
- [Stanford Named Entity Recognizer (NER)](https://nlp.stanford.edu/software/CRF-NER.html) for person, organisation and location recognition.
- [WordHoard](https://wordhoard.northwestern.edu/userman/index.html) web application for the close reading and scholarly analysis of deeply tagged texts, from Northwestern University.
- [WORDij Semantic Network Tools](https://www.wordij.net/index.html) is downloadable software for natural language processing. It can process unstructured text from sources such as social media, news, speeches, focus groups, interviews, email, and web sites. 
- [CLAWS part of speech tagger](https://ucrel.lancs.ac.uk/claws/) for corpus annotation for English text, developed by UCREL at Lancaster University.{% endcapture %}{% include card.html header="Open source (free) tools" text=text %}

{% capture text %}
Try this [activity](https://griffithunilibrary.github.io/data-vis-basics/content/5-voyant.html) using [Voyant tools](https://voyant-tools.org/). Look at the results, think how you might use it for analysis and the limitations of the tool.{% endcapture %} {% include card.html header="Voyant tools activity" text=text %}

{% capture text %}
- [R](https://www.rstudio.com/products/rstudio/) & [R Studio](https://www.rstudio.com/) : network analysis, topic modeling, classification/clustering, named entity recognition, sentiment analysis 
- [Python](https://www.python.org/) : network analysis, topic modeling, classification/clustering, named entity recognition, sentiment analysis

##### Coding tutorials for text mining and analysis
- [Beginner R & Python workshops](https://www.griffith.edu.au/eresearch-services/hacky-hour) are available from Griffith's eResearch services throughout the year. 
- [Constellate tutorials](https://constellate-org.libraryproxy.griffith.edu.au/) a series of lessons to help you learn about programming in Python, text analysis, and the Constellate platform for JSTOR.
- [Programming Historian](https://programminghistorian.org/en/lessons/)  novice-friendly, peer-reviewed tutorials to help humanists learn a wide range of digital tools, techniques, and workflows. These include lesons in R and Python. 
- [GLAM Workbench tutorials](https://glam-workbench.net/getting-started/) learn how to use the GLAM Workbench, [Jupyter Notebook](https://jupyter.org/) and Python to extract and analyse data from Australia's galleries libraries, archives and museums.
- [Top 5 Unknown Sentiment Analysis Projects On Github To Help You Through Your NLP Projects](https://medium.com/analytics-vidhya/top-5-unknown-sentiment-analysis-projects-on-github-to-help-you-through-your-nlp-projects-8d8f195e80fc) 
- [Language Technology and Data Analysis Laboratory (LADAL) Tutorials](https://ladal.edu.au/tutorials.html) provides online text analysis tutorials in R.{% endcapture %}{% include card.html header="Coding for text mining and analysis" text=text %}

{% capture text %}
Note: Refer to software used for your research in methods notes. Attribute software developers by citation e.g. 

Sinclair, Stéfan and Geoffrey Rockwell, 2016. *Voyant Tools*. Web. http://voyant-tools.org/.{% endcapture %}{% include alert.html text=text color="info" %} 

-----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/6-prepare-av.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/8-visualising_data.html">NEXT --></a>
</p>
