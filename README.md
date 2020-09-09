# CSV Fingerprint --- But With Colormaps!

CSV Fingerprint is a small app that generates qualitative visualizations of any CSV file to help debug any formatting issues. 
Each cell is colored according to its type. Strings are yellow, empty values are red. 
Decimals are color-coded with the [plasma colormap](https://matplotlib.org/3.1.0/tutorials/colors/colormaps.html); integers with the [viridis colormap](https://matplotlib.org/3.1.0/tutorials/colors/colormaps.html).

Be patient, loading takes a while.

# Installation

First, clone the repo using git.

    `git clone git://github.com/gauchm/csv-fingerprint`


Next, from the terminal, run the following command from within the project
directory.

    `python -m http.server`

This will start a webserver running where you can access the app from a browser
using the following url:

    http://localhost:8000
