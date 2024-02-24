# This is the third excersise for the course Applied Machine Learning (Roget’s Thesaurus in the 21st Century)
## By: George Artopoulos (8200016)

### Project Structure

The project contains the following files:

- `README.md`: This file, with the project description and instructions.
- `Scraping.ipynb`: A Jupyter notebook with the code for scraping the nessessary data from the Project Gutenberg website.
- `Clustering.ipynb`: A Jupyter notebook with the code for clustering in two hierarchical levels based on the scraped data.
- `Classification.ipynb`: A Jupyter notebook with the code for the classification in two hierarchical levels based on the scraped data.
- `pyproject.toml`: For poetry support.
- `poetry.lock`: For poetry support.
- `ML_Assignment_3`: Directory needed for poetry support.
- `tests`: Directory needed for poetry support.
- `bold_words_with_numbers3.txt`: The file with the scraped data.
- `rogets_thesaurus.ipynb`: The with the description of the assignment.

### Project Description

Task 1: Scraping

***Get Roget's Thesaurus Classification from Project Gutenberg***. Get the categorisation (and the words belonging in each category), save them and store them in the way that you deem most convenient for processing.

Task 2: Embeddings

***Get Word Embeddings***. It is up to you to find the embeddings; you can use any of the available models. Older models like word2vec, GloVe, BERT, etc., may be easier to use, but recent models like Llama 2 and Mistral have been trained on larger corpora. OpenAI and Google offer their embeddings through APIs, but they are not free.

You should think about how to store the embeddings you retrieve. You may use plain files (e.g., JSON, CSV) and vanilla Python, or a vector database.

Task 3: Clustering

Check whether ***unsupervised Machine Learning methods*** can arrive at classifications that are comparable to the Roget's Thesaurus Classification. You can use any clustering method of your choice (experiment freely). You must decide how to measure the agreement between the clusters you find and the classes defined by Roget's Thesaurus and report your results accordingly. The comparison will be at the class level (six classes) and the section / division level (so there must be two different clusterings, unless you can find good results with hierarchical clustering)

Task 4: Classification

Now flip over to ***supervised Machine Learning methods***. You must experiment and come up with the best classification method, whose input will be a word and its target will be its class, or its section / devision (so there must be two different models).

### Instructions

After cloning the repository, you can download the necessary dependencies with poetry by running the following command (if you have poetry installed on your system):
``` poetry install ```
