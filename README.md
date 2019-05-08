# Pretrained-Embeddings-Exploration
Exploring different pretrained embeddings for e.g. word association 


[GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/)

Use the [Wikipedia 2014 + Gigaword 5](http://nlp.stanford.edu/data/glove.6B.zip) word vector data set.
This contains text files with vectors of different dimensions.  The text entries are formatted with the word first, followed by some amount of real, numerical data representing that word's vector.

The [bcolz](https://github.com/Blosc/bcolz) package can be used to compress the data (>400 tokens!).  I had an easier time installing with conda over pip: <br>
`conda install bcolz`
