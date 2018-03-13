+++
title = "Rectangular grating"
weight = 11
+++

### Rectangular grating

In this example we simulate the scattering from infinite 1D repetition of rectangular patches (rectangular grating). This is done by using the interference function of a 1D lattice together with very long boxes. While being similar to the [Interference 1D lattice]({{% relref "documentation/python-examples/interference-functions/Interference1DLattice.md" %}}) example, this example explains the lattice orientation in more details.

* By-default, the axis of the one-dimensional lattice coincides with the $x$-axis of the reference cartesian frame, so it coinsides with the beam direction.
* Long boxes are placed along a one-dimensional lattice on top of substrate, the lattice_length parameter corresponds to the grating period.
* The size of boxes is initially chosen to form a grating which is perpendicular to the beam (long side of the box is along $y$-axis).
* Please keep in mind, that `length`, `width`, `height` in the `FormFactorBox(length, width, height)` constructor correspond to the directions in the $x,y,z$ axes, in that order, so to achieve the desired setup we use the values: `length`= $10$ nm, `width`= $10000$ nm, `height`= $10$ nm.
* The whole grating is rotated at the end by an angle of $45^{\circ}$ with respect to the beam axis. This is achieved by rotating _both_ the 1D lattice and the long boxes (see lines 25 and 34).
* To avoid the problem of rapidly oscillating form factors of long boxes (see [this example]({{% relref "documentation/python-examples/complex-shapes/LargeParticlesFormFactor.md" %}}) for more details), the simulation is performed in monte carlo integration mode.

{{< galleryscg >}}
{{< figscg src="/files/Examples_images/real_space_images/RectangularGrating_setup.jpg" width="350px" caption="Real-space model">}}
{{< figscg src="/files/Examples_images/PyExamples/RectangularGrating.png" width="350px" caption="Intensity image">}}
{{< /galleryscg >}}

#### Python script:
{{% highlightfile 
file="/static/files/python/simulation/ex03_InterferenceFunctions/RectangularGrating.py" language="python" %}}
