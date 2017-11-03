# Introduction to Plotting in Python
This repository contains Python notebooks as an introduction to introductory plotting in Python for the purposes of climate / atmospheric science applications.

Please email dcw32.wade -at- gmail.com with any comments!

## Getting started
To run these notebooks, you need to first install Python. I recommend doing this using Anaconda - install this then create a new Python environment.

For a minimal anaconda based installation:
`conda create -n plotting_intro python=2.7 cartopy jupyter netCDF4 pandas`

Then fire up jupyter notebook from the command line and use the `plotting_intro` kernal.

To download the github repository run `git clone https://github.com/dcw32/plotting-intro.git`.

In the `data/` directory run `wget http://berkeleyearth.lbl.gov/auto/Global/Gridded/Land_and_Ocean_LatLong1.nc` to download the Berkeley Earth data.

## Notebooks

`plotting_intro` is an introduction to plotting in Python, using publicly available data:
* Column ozone from Halley Bay (Farman et al 1985) - the first observations of the ozone hole 
<img src="https://github.com/dcw32/plotting-intro/raw/master/img/farman.png" width="400px" />

* The North Atlantic Oscillation (NAO) - a key mode of variability in the North Atlantic
<img src="https://github.com/dcw32/plotting-intro/raw/master/img/nao.png" width="400px" />

* The Berkeley Earth Surface Temperature (BEST) dataset - how have surface temperatures changed in recent years?
<img src="https://github.com/dcw32/plotting-intro/raw/master/img/best.png" width="400px" />

* Surface ozone trends and spectral analysis - Jungfraujoch and Mace Head (To Come)

Along the way you'll learn how to make scatter plots, line plots, error bars, bar charts, contour plots and use cartopy to project data onto a world map.

[comment]: <> (Note that matplotlib is used instead of alternatives like Seaborn. Whilst Seaborn makes nicer plots without much effort, it is much more difficult to customize - I personally dislike the blue background it seems to always plot and think it distracts from the data.)

`classic_paleo` introduces some iconic oxygen isotope datasets:
* Zachos curve: The last ~65 million years (Zachos et al 2001)
![zachos](https://github.com/dcw32/plotting-intro/raw/master/img/zachos.png)
* LR04: The last ~5 million years (Lisiecki and Raymo, 2005)
![lr04](https://github.com/dcw32/plotting-intro/raw/master/img/lr2004.png)
* Petit: The last 420 000 years (Petit et al, 1999)

This contains a broad range of techiques like scatter plots but some other more specific techniques like twin axes, inset plots, dummy axes etc.
