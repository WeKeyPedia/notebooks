# notebooks

Labnotes about data exploration and visualization of wikipedia pages corpora.

## about the datasets

All the initial content and the produced datasets are stored as `csv` and `gexf` are stored in the [`data`](https://github.com/WeKeyPedia/notebooks/tree/master/geometry/data) folder of each topic folders.

## list of geometry topics

This analysis is about the set of pages imported from the wikipedia [List of geometry topics](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/time%20series.ipynb) page. All the muscle for data retrieval work has been provided using the [`wekeypedia/python-toolkit/analysis-data-retrieval.py`](https://github.com/WeKeyPedia/toolkit-python/blob/master/analysis-data.py) macro.

### dataset content

- pages: 303
- editors: 15857
- revisions: 101462

### analysis

- [multivariate analysis](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/multivariate%20analysis.ipynb): main exploration and results from the the geometry pages dataset
- [time series](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/time%20series.ipynb): pageviews and revisions time series of all pages 
- [page explorer](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/page%20explorer.ipynb): a notebook to explore data about individual pages. Very helpfull if you are looking for local relationships. This includes all analytics used by knwoledge path reconstruction
- [construction of the hyperlink graph](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/hyperlinks%network.ipynb): reconstruction of the natural hyperlink network between the corpus pages. Also add an extension to the graph of page names apparitions
- [reading map based on a reduced graph of hyperlink terms](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/reading%20map%20based%20upon%20reduced%20hyperlinks%20graph.ipynb)
- [construction of the pages-editors bi-partite graph](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/construction%20of%20the%20pages-editors%20bi-partite%20graph.ipynb): construction of a bi-partite graph made of pages and editors. Also build a page-page graph based on the projection of the previous bi-partite where pages are linked if they share an editor
- [building a reading map based on a reduced graph of co-edited pages](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/reading%20map%20based%20on%20reduced%20co-edited%20pages%20graph.ipynb): a first trial at building a stronger reading map based upon a strategy using co-edited pages 
network instead of hyperlinks network. This include a lot of mid-range lifting involving [networkx](http://networkx.github.io/)
- [index of bots](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/geometry/index%20of%20bots.ipynb): List of bots active in the corpus

## sociology

### dataset content

- pages: 1239
- editors: 81604
- revisions: 697011

## wisdom

- pages: 4

- [parsing and decoding wikipedia page diffs](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/wisdom/parsing%20wikipedia%20diff.ipynb): a guide about using the [wekeypedia toolkit](http://github.com/wekeypedia/toolkit-python) to make sense of diffs
- [words of love and wisdom](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/wisdom/words%20of%20wisdom%20and%20love.ipynb): numerical exploration of terms distributions over the corpus pages
- [find love on wikipedia with NLTK](http://nbviewer.ipython.org/github/WeKeyPedia/notebooks/blob/master/wisdom/find%20love%20with%20nltk.ipynb): exploitation of the work on diffs to extract signs of love on wikipedia