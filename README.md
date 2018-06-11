## Digital-Research-Tools-and-Methods

Here are some tools, tutorials and other resources (nearly all free) I've found useful and interesting:


# Web-scraping tools:
*Import.io: point-and-click webscraper! Also works to do point-and-click data cleaning for HTML files. 
*ChromeScraper (I haven't used it yet, but it is a point-and-click webscraper like Import.io)
*NodeXL: import network data from sites like Twitter and Youtube, and do network analysis
*Gephi's Plug-In StreamingTwitterImporter: Gephi is a point-and-click network analytic/visualization program, and has a plug in to stream Twitter data
*Scraper
*SelectorGadget
*BeautifulSoup: Python library for webscraping.

# Text Mining and other Digital Humanities tools:
Tapor Tools: text analysis tool
Mallet: tool for topic modeling, also usable in a point-and-click format
Voyant: simple point-and-click text analysis tool. Note that data uploaded to this becomes public. 
Great, extensive list at USC text mining libguide

# Data Visualization tools:
Tableau: excellent point-and-click data visualization, free version available to public (Tableau public) and students (Tableau desktop). 
Gephi: point-and-click network analysis/visualization, also has a plug in to scrape data from Twitter!

# Other great tools:
OpenRefine: point-and-click data cleaning!
Overleaf: nice site to create and keep your LaTex documents. It also lets you collaborate on LaTex documents, and see the PDF updated as you update your LaTex document
Jupyter Notebooks in Python - nice interface to work with Python, especially if you're just getting started. 
Visual Basic - great for debugging Python and other programming languages, clearly points out any errors!
A massive database of digital research tools organized by tasks, called "DIRT"

# Management Tools:
EndNote: Keep track of citations. Download the Endnote plug in for Word and you can easily cite while you write.

# Data:
USC List of Databases that allow text mining
USC List of Free Corpora for Text Mining 




# Methods & Concepts:

Word embeddings, and, specifically, Word2Vec, AdaGram, and GloVe. 
Word embeddings refers to methods like Word2Vec which model language as an n-dimensional vector space. If an n-dimensional vector space is confusing, think about a 2D vector space as a plane, and 3D vector space as a box. Although not easily imaginable, Word2Vec works in vector space of a few hundred dimensions. Each dimension corresponds to a salient dimension of language in a corpus, such as gender or tense, although in practice it is unknown what abstract concept the dimension actually corresponds to. Word2Vec learns this vector space by predicting a word from its context (or vice versa). In the process, each word in the corpus is mapped onto this vector space, such that words with more similar meanings in the corpus are located closer together in the vector space.  Word2Vec may be implemented in Python through the Gensim package. 


Social networks (and networks, more broadly)
Network methods and theories provide a different way to think about data. Rather than focusing on attributes of each thing (like a person) in the data set, a network perspective focuses on the relationships between things (or people). From a network perspective, we might look at the presence/absence, or strength of relationships between people, whether the relationships are reciprocal, and if there are any patterns such as tightly knit cliques or particular people who are well-connected to others in the network. 
