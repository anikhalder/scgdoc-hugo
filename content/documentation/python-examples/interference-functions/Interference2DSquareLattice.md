+++
title = "Interference 2D Square Lattice"
weight = 11
+++

### Interference 2D Square Lattice

Scattering from cylindrical particles distributed along a square lattice.

* Cylinders with radii and heights of $3$ nm are deposited on a substrate.
* Because of the presence of the substrate layer the simulation is run using the DWBA.
* The particles are distributed along a square lattice with a lattice length of $25$ nm.
* The main axes are parallel to the $x$-axis and $y$-axis of the reference Cartesian frame, respectively.
* The lattice is initialized by placing a cylinder at the origin.
* The incident beam is characterized by a wavelength of $1$ $\unicode{x212B}$.
* The incident angles are $\alpha\_i = 0.2 ^{\circ}$ and $\phi\_i = 0^{\circ}$.

{{< galleryscg >}}
{{< figscg src="/files/Examples_images/real_space_images/Interference2DSquareLattice_setup.jpg" width="350px" caption="Real-space model">}}
{{< figscg src="/files/Examples_images/PyExamples/Interference2DSquareLattice.png" width="350px" caption="Intensity image">}}
{{< /galleryscg >}}

#### Python script: 
{{% highlightfile file="/static/files/python/simulation/ex03_InterferenceFunctions/Interference2DSquareLattice.py" language="python" %}}
