# Topic Modelling  - Threats and Risks

Research questions and aims of this demo: 
- What is the culture of the cryptomarket forums? 
- What are the major topics of discussion?
- How do you use machine learning to find out?
- How do you pre-process data?
- How do you present and visualise your analysis?

## How to set up

Create a conda env using the environment yaml file in the root of this repo:

`conda env create -f environment.yml`

---

One manual step to download a dependency, make sure you are in the environment just created above:

`conda activate threats-risks-topic-modelling`

`python -m spacy download en_core_web_sm`

---

Create a `data/` folder in the root of the repo and place all of the .csv dataset files we were supplied in there.

It should look like:

```text
data/
README.md
topic_modeling_Gensim.ipynb
.gitignore
```

#### Credits

Code based on [this blog post](https://towardsdatascience.com/topic-modelling-in-python-with-nltk-and-gensim-4ef03213cd21) to provide a quick presentation on how to apply topic modelling with python.
