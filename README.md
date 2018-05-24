# Toeing the party manifold

Interactive visualization of dimensionality reduction techniques applied to US congressional voting data.

<iframe src="https://toeing-party-manifold.herokuapp.com/" width="840" height="675"></iframe>

The essential workflow, each step corresponding to a Jupyter notebook:

1. [load.ipynb](https://github.com/carMartinez/toeing-party-manifold/blob/master/load.ipynb) Load/clean/encode congressional voting data and load legislator metainfo.
2. [manifold.ipynb](https://github.com/carMartinez/toeing-party-manifold/blob/master/manifold.ipynb) Apply several dimensionality reduction algorithms to the encoded voting data
3. [dash.ipynb](https://github.com/carMartinez/toeing-party-manifold/blob/master/dash.ipynb) Visualize the embeddings in 2- and 3-dimensions with a Dash app.

A more thorough high-level overview is available [here](http://cmartinez.io/toeing-party-manifold/). Low-level details are
explained within the notebooks.
