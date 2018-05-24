# Toeing the party manifold

Interactive visualization of dimensionality reduction techniques applied to US congressional voting data.

![Snapshot of visualization](https://github.com/carMartinez/toeing-party-manifold/blob/master/img/outliers.png)

The interactive visualization itself and a more thorough, high-level overview of
the project are available
[here](http://cmartinez.io/toeing-party-manifold/). Low-level details are
explained within the Jupyter notebooks.

The essential workflow, each step corresponding to a notebook:

1. [load.ipynb](https://github.com/carMartinez/toeing-party-manifold/blob/master/load.ipynb) Load/clean/encode congressional voting data and load legislator metainfo.
2. [manifold.ipynb](https://github.com/carMartinez/toeing-party-manifold/blob/master/manifold.ipynb) Apply several dimensionality reduction algorithms to the encoded voting data
3. [dash.ipynb](https://github.com/carMartinez/toeing-party-manifold/blob/master/dash.ipynb) Visualize the embeddings in 2- and 3-dimensions with a Dash app.
