# Topic Modelling  - Threats and Risks

Research question: How can you understand the culture of the forums? What are the major topics of discussion?

## How to set up

Create a conda env using the environment yaml file in the root of this repo:

`conda env create -f environment.yml`

One manual step to download a dependency, make sure you are in the environment just created above:

`conda activate threats-risks-topic-modelling`

`python -m spacy download en_core_web_sm`

Create a `data/` folder in the root of the repo and place all of the .csv dataset files in there.

It should look like:

```text
data/
README.md
topic_modeling_Gensim.ipynb
.gitignore
```



