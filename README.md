# notebooks

Labnotes about data exploration and visualization

## geometry dataset

This analysis is about the set of pages imported from the wikipedia [List of geometry topics](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/time%20series.ipynb) page. All the muscle for data retrieval work has been provided using the [`wekeypedia/python-toolkit/analysis-data-retrieval.py`](https://github.com/WeKeyPedia/toolkit-python/blob/master/analysis-data.py) macro.

- [multivariate analysis](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/multivariate%20analysis.ipynb): main exploration and results from the the geometry pages dataset
- [time series](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/time%20series.ipynb): Pageviews and revisions time series of all pages 
- [construction of the pages-editors bi-partite graph](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/construction%20of%20the%20pages-editors%20bi-partite%20graph.ipynb): construction of a bi-partite graph made of pages and editors. Also build a page-page graph based on the projection of the previous bi-partite where pages are linked if they share an editor
- [page explorer](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/page%20explorer.ipynb): a notebook to explore data about individual pages. Very helpfull if you are looking for local relationships. This includes all analytics used by knwoledge path reconstruction

Both the initial content and the produced dataset are stored as `csv` and `gexf` are store in the [`data`](https://github.com/WeKeyPedia/notebooks/tree/master/geometry/data).