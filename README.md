# PENDING - -
# Movie Review Text Classification
## Classifying Positive and Negative Review with NLP

* **Author**: Miguel Santana

Thank you for reviewing this repository. The author's contact info, blog post, sources and social media profiles are listed below under **further information.**

The contents of this repository detail an analysis of 6000 movie reviews of which 3000 are positive and 3000 are negative. In this particular case, the text has been preprocessed and the labels are provided in order to assess performance. The analysis will provide insight into method's used by NLP professionals to evaluate text for businesses.

### Project Framework

![!](/images/OSEMN.png)

**Data processing and analysis is completed using the OSEMN framework. The structure includes: Obtaining the data, Scrubbing (processing), Exploratory Data Analysis, Statistical Modeling and Interpretation of the Results.**

### The Data

The dataset is originally sourced from Stanford Artificial Intelligence Laboratory (SAIL) but was provided via Udemy. The Udemy citation is available below under **sources.** Please visit [ai.stanford.edu](http://ai.stanford.edu/~amaas/data/sentiment/) for more information on this dataset.

## Scrubbing/Data Cleaning 

**Key Decisions**

* Address whitespace strings
* Drop null values

## Exploratory Data Analysis 

#### Feature Relationships

**Length of Reviews**

![!](/images/lengthofreviews.jpg)

**Positive vs. Negative**

![!](/images/positivenegativelength.jpg)

## Statistical Modeling 

Modeling:
* Feature | Target
* Count Vectorization
* Test | Train Split
* MultinomialNB Classifier
* LinearSVC Classifier
* Pipeline: Top Model & TFIDF Vectorizer

### Model Validation

Model performance was evaluated using accuracy as a metric. This decision was made as a result of the balanced positive and negative classes. 

**MultinomialNB Classifier**
![!](/images/MNB_modelvis.jpg)

MultinomialNB Classifier Overall Accuracy: 0.91

**LinearSVC Classifier**
![!](/images/LSVC_modelvis.jpg)

LinearSVC Classifier Overall Accuracy:: 0.90

### Final Model
**LinearSVC Pipeline: Overall Accuracy:: 0.92**

## Interpreting Results | Used Cases

The model was able to predict () with an (metric) score of (score).

This type of an analysis is popular in business case ()

It allows companies to better ()

## Limitations

Limitations to this type of statistical modeling are ()

Challenges for this analysis are ()

## Future Work

Future work should include () data in order to ()

This will allow () to be able to () better and ultimately leverage statistical modeling in order to ()

### Further Information
Please review the narrative of our analysis in [our jupyter notebook](./jupyter_notebook.ipynb) or review our [presentation](/powerpoint/powerpoint.pdf)

A blog post on this analysis can be found on [Medium.](website)

For any additional questions, please reach out via email at santana2.miguel@gmail.com, on [LinkedIn](https://www.linkedin.com/in/miguel-angel-santana-ii-mba-51467276/) or on [Twitter.](https://twitter.com/msantana_ds)

#### Sources

Additional analysis, notes and file sources can be found on Udemy. 

* Course Name: NLP - Natural Language Processing | Jose Portilla

##### Repository Structure:

```

├── README.md               <- The top-level README for reviewers of this project.
├── jupyter_notebook.ipynb     <- narrative documentation of analysis in jupyter notebook
├── presentation.pdf        <- pdf version of project presentation

```

