# Chaos
#### Visualizations connecting chaos theory, fractals, and  the logistic map!

###### Written by [Jonny Hyman](www.jonnyhyman.com), 2020
###### MIT License

This is not a library, but rather a collection of standalone scripts! As such, there is a bit of code duplication between scripts.

#### Requirements
- [Python 3.6+](https://www.anaconda.com/distribution/) (tested on Python 3.6 and Python 3.7)
- [Numpy](https://numpy.org) package : `pip install numpy`
- [Numba](https://numba.pydata.org) package : `pip install numba`

----

## Logistic Map - Interactive
`python logistic_interactive.py`
![Interactive](https://github.com/jonnyhyman/Chaos/blob/master/images/logistic-interactive.png?raw=true)

#### Additional Requirements
- PyQt5 : `pip install pyqt5`
- PyQtGraph : `pip install pyqtgraph`

This visualization creates a time series cobweb plot, time series graph, and bifurcation plot for visualizing the logistic map.

#### Shortcuts:
- Spacebar: play/pause
- Backspace: reset view & animation

----

## 3D Mandelbrot Set
`python logistic_mandelbrot.py`
![Mandelbrot Set within Logistic Map GIF](https://github.com/jonnyhyman/Chaos/blob/master/images/logistic-mandelbrot.gif?raw=true)

#### Additional Requirements
- [Vispy](http://vispy.org) : `pip install vispy`
- [Matplotlib](https://matplotlib.org) : `pip install matplotlib`
- [PyOpenGL](https://pypi.org/project/PyOpenGL/) : `pip install pyopengl`
- [ffmpeg](https://www.ffmpeg.org) if you want to auto-stitch rendered frames to .movs
  - macOS: [Install homebrew](https://brew.sh) then `brew install ffmpeg`
  - Windows: [Install chocolatey](https://chocolatey.org) then `choco install ffmpeg`

----

## Logistic Map Zoom
`python logistic_zoom.py`
![Logistic Map Zoom GIF](https://github.com/jonnyhyman/Chaos/blob/master/images/logistic-zoom.gif?raw=true)

- [Vispy](http://vispy.org) : `pip install vispy`
  - Note: The final version of the visualization as seen on YouTube used a custom version of Vispy, modified to improve the appearance of axes. I have not released this and don't plan to, but if you really need it please post in Issues a feature request.