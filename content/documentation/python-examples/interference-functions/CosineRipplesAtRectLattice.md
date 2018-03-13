+++
title = "Cosine ripples on Rectangular Lattice"
weight = 11
+++

### Cosine ripples on Rectangular Lattice

Scattering from elongated particles distributed along a two-dimensional rectangular lattice.

* Each particle has a sinusoidal profile ("Ripple1" form factor) with a length of $100$ nm, a width of $20$ nm and a height of $4$ nm.
* They are placed along a rectangular lattice on top of a substrate.
* This lattice is characterized by a lattice length of $200$ nm in the direction of the long axis of the particles and of $50$ nm in the perpendicular direction.
* The lattice's base vectors coincide with the reference Cartesian frame.
* The wavelength is equal to $1.6$ $\unicode{x212B}$.
* The incident angles are $\alpha\_i = 0.3 ^{\circ}$ and $\phi\_i = 0^{\circ}$.


{{< galleryscg >}}
{{< figscg src="/files/Examples_images/real_space_images/CosineRipplesAtRectLattice_setup.jpg" width="350px" caption="Real-space model">}}
{{< figscg src="/files/Examples_images/PyExamples/CosineRipplesAtRectLattice.png" width="350px" caption="Intensity image">}}
{{< /galleryscg >}}

#### Python script:
{{% highlightfile file="/static/files/python/simulation/ex03_InterferenceFunctions/CosineRipplesAtRectLattice.py" language="python" %}}