# Description:

`BERTopic` analysis of comments across stance (flexibility and HHFKA) across 2 years (2017 and 2020). 
`BERTopic` is essentially a topic modeling approach that leverages pre-trained language models (i.e. `BERT`) to group similar documents together and aim to uncover the semantic topics behind these clustered documents. 

# Table of Contents
> data  
> > interim_data  
> > raw_data  
> > plots

> Part_1_data_cleaning.ipynb  
> Part_2_BERTopic.ipynb  
> Part_3_plot.ipynb  


Data contains all the neccessary data used in the analysis. 
- `interim_data` includes all the cleaned / preprocessed data and data of the documents grouped into their respective topic clusters. 
- `plots` contains all the plots used to visualize the cluster of comments spanning each stance (flexibility and HHFKA) across 2 years (2017 and 2020).

# requirements

### Compute requirements
One GPU of at least 12GB of VRAM 

The following packages are required
### Required Packages

1. **BERTopic** - `bertopic`
2. **KeyBERT** - `keybert`
3. **Transformers** - `transformers`
4. **scikit-learn** - `scikit-learn`
5. **Pandas** - `pandas`
6. **NumPy** - `numpy`
7. **tqdm** - `tqdm`
8. **regex** - `re` (standard library in Python)
9. **UMAP** - `umap-learn`
10. **Plotly** - `plotly`
11. **Plotly.colors** - `plotly.colors` (accessed within `plotly`)

```{bash}
pip install bertopic keybert transformers scikit-learn pandas numpy tqdm umap-learn plotly
```

# Replication
Simply run the `.ipynb` files for replication. 
