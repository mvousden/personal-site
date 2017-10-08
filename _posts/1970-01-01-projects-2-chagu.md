---
category: Projects
title: Chagu
anchorID: chagu
imagePath: project_chagu.png
externalUrl: https://github.com/mvousden/chagu
---

Vector field visualisation using [VTK](http://www.vtk.org/) and
[Python](https://www.python.org/).

Chagu's objective is to create quality renders and animations of results from
micromagnetic simulations with [few lines of code](https://github.com/mvousden/
chagu/blob/development/example/example_tiny.py).
The interface to [VTK](http://www.vtk.org/) is [complicated](http://www.vtk.org
/doc/nightly/html/classvtkRenderer.html), and there is no object that describes
the VTK pipeline explicitly, which is the concept responsible for connecting
different visualisation elements together.
Chagu uses its Visualisation class to structure and control visualisation in
real-time.