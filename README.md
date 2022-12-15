# Algorithmic Methods of Data Mining Homeworks

## Homework 2

The homework was divided in 3 sections:

1. The first one in which we had to answer to some RQs on a [kaggle dataset](https://www.kaggle.com/datasets/shmalex/instagram-dataset) about **instagram_profiles.csv**, **instagram_locations.csv**, **instagram_posts.csv**.
2. A Command Line Question about the **instagram_posts.csv**.
3. Some Algorithmic Questions.

### Team

- Alessandro Sottile [[Github](https://github.com/Sottix99)] [[Linkedin](https://www.linkedin.com/in/alessandro-sottile-181863158/)].
- Davide Vigneri [[Github](https://github.com/VigneriDavide)] [[Linkedin](https://www.linkedin.com/in/davide-vigneri-59a56021a/)].
- Mario Edoardo Pandolfo [[Github](https://github.com/JRhin)] [[Linkedin](https://www.linkedin.com/in/jrhin/)].

### Repository

Inside `homework2` there are two files:

- `main.ipynb`:  a Jupyter notebook that contains all the answers to your research and theoretical questions. Clicking [here](https://nbviewer.org/github/JRhin/algorithmic-methods-of-data-mining-homeworks/blob/main/homework2/main.ipynb) you can find the nbviewer version of the notebook.
- `CommandLine.sh`: a bash shell script file contains the prepared script to answer to the command line question.

## Homework 3

The homework was divided in 3 sections:

1. The first one in which we had to scrape a site ([Atlas Obscura](https://www.atlasobscura.com/)), collect data about locations then we had to build two types of search engines to retrieve documents (the locations) that better match with a given query.
2. A Command Line Question about the data collected from the site.
3. Some Algorithmic Questions.

### Team

- Ilaria Petrucci [[Github](https://github.com/ilapetr)].
- Nicola Grieco [[Github](https://github.com/nicolagrieco00)] [[Linkedin](https://www.linkedin.com/in/nicola-grieco-36a993233/)].
- Mario Edoardo Pandolfo [[Github](https://github.com/JRhin)] [[Linkedin](https://www.linkedin.com/in/jrhin/)].

### Repository

This git repository contains our solution for the homework 3.

There are three files:

- `main.ipynb`:  a Jupyter notebook that contains all the answers to your research and theoretical questions. Clicking [here](https://nbviewer.org/github/JRhin/algorithmic-methods-of-data-mining-homeworks/blob/main/homework3/main.ipynb) you can find the nbviewer version of the notebook.

- `CommandLine.sh`: a bash shell script file contains the prepared script to answer to the command line question.

- `search_engines.py`: A python file containing all the classes that we have defined to create the two search engines.

  - `Vocabulary()`: The vocabulary of a `pd.DataFrame`.
  - `Index()`: The inverted index.
  - `SearchEngine()`: Our first simple search engine based on tf-idf & cosine similarity.
  - `OurSearchEngine()`: The more complex search engine.

  An example usage of these classes can be found in the `main.ipynb` notebook.

  **Note**: This python file contains only the modular classes, so there is no scraping or preprocessing section, this is because these parts depend on the data structure, while the classes contained don't: they require the data to be preprocessed (As usually an example can be found in the `main.ipynb` notebook).

## Homework 4

The homework was divided in 4 sections:

1. We had to perform two works on a particular [kaggle dataset](https://www.kaggle.com/datasets/shivamb/bank-customer-segmentation).
   1. At first we had to retrieve similar users of a query user, using a Locality Sensitive Hashing approach.
   2. Then in the second work we had to perform user clustering.

2. A Command Line Question about the data collected from the site.
3. An Algorithmic Question.

### Team

- Eric Rubia Aguilera [[Github](https://github.com/ericrubia99)].
- Vahid Ghanbarizadeh [[Github](https://github.com/Vah1d)].
- Mario Edoardo Pandolfo [[Github](https://github.com/JRhin)] [[Linkedin](https://www.linkedin.com/in/jrhin/)].

### Repository

This git repository contains our solution for the homework 4.

There are two files:

- `main.ipynb`:  a Jupyter notebook that contains all the answers to your research and theoretical questions. Clicking [here](https://nbviewer.org/github/JRhin/algorithmic-methods-of-data-mining-homeworks/blob/main/homework4/main.ipynb) you can find the nbviewer version of the notebook.

- `CommandLine.sh`: a bash shell script file contains the prepared script to answer to the command line question.
