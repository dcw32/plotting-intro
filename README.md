# Introduction to Plotting in Python
This repository contains Python notebooks as an introduction to introductory plotting in Python for the purposes of climate / atmospheric science applications.

## Getting started
To run these notebooks, you need to first install Python. I recommend doing this using Anaconda - install this then create a new Python environment.

For a minimal anaconda based installation:
`conda create -n plotting_intro python=2.7 cartopy jupyter netCDF4`

Then fire up jupyter notebook from the command line and use the `plotting_intro` kernal.

## Notebooks

`plotting_intro` is an introduction to plotting in Python, using publicly available data:
* Column ozone from Halley Bay (Farman et al 1985) - the first observations of the ozone hole 
![farman](https://github.com/dcw32/plotting-intro/raw/master/img/farman.png | width=300)
<img src="https://github.com/dcw32/plotting-intro/raw/master/img/farman.png" height="300px" />
* The North Atlantic Oscillation (NAO) - a key mode of variability in the North Atlantic
![nao](https://github.com/dcw32/plotting-intro/raw/master/img/nao.png)
* The Berkeley Earth Surface Temperature (BEST) dataset - how have surface temperatures changed in recent years?
![best](https://github.com/dcw32/plotting-intro/raw/master/img/best.png)
* Surface ozone trends and spectral analysis - Jungfraujoch and Mace Head (To Come)

Along the way you'll learn how to make scatter plots, line plots, error bars, bar charts, contour plots and use cartopy to project data onto a world map.

`classic_paleo` introduced some iconic oxygen isotope datasets:
* Zachos curve: The last ~65 million years (Zachos et al 2001)
![zachos](https://github.com/dcw32/plotting-intro/raw/master/img/zachos.png)
* LR04: The last ~5 million years (Lisiecki and Raymo, 2005)
![lr04](https://github.com/dcw32/plotting-intro/raw/master/img/lr2004.png)
* Petit: The last 420 000 years (Petit et al, 1999)

This contains a broad range of techiques like scatter plots but some other techniques like twin axes, inset plots etc.
