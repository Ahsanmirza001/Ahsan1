# Working With Text Data
The goal of this guide is to explore some of the main scikit-learn tools on a single practical task: analyzing a collection of text documents (newsgroups posts) on twenty different topics.
*.pyc
.DS_Store
*.pdf
#Tutorial setup
workspace

# output of the sphinx build of the documentation
tutorial/_build

# datasets to be fetched from the web and cached locally
data/twenty_newsgroups/20news-bydate.tar.gz
data/twenty_newsgroups/20news-bydate-train
data/twenty_newsgroups/20news-bydate-test

data/movie_reviews/txt_sentoken
data/movie_reviews/poldata.README.2.0

data/languages/paragraphs
data/languages/short_paragraphs
data/languages/html

data/labeled_faces_wild/lfw_preprocessed/
© 2020 GitHub, Inc.
Here are a few suggestions to help further your scikit-learn intuition upon the completion of this tutorial:

Try playing around with the analyzer and token normalisation under :class:`CountVectorizer`.
If you don't have labels, try using :ref:`Clustering <sphx_glr_auto_examples_text_plot_document_clustering.py>` on your problem.
If you have multiple labels per document, e.g categories, have a look at the :ref:`Multiclass and multilabel section <multiclass>`.
Try using :ref:`Truncated SVD <LSA>` for latent semantic analysis.
Have a look at using :ref:`Out-of-core Classification <sphx_glr_auto_examples_applications_plot_out_of_core_classification.py>` to learn from data that would not fit into the computer main memory.
Have a look at the :ref:`Hashing Vectorizer <hashing_vectorizer>` as a memory efficient alternative to :class:`CountVectorizer`.
