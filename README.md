CompassView
===========

Class CompassView extends Android ImageView to perform cool, real-life animation of objects
such compass needle in magnetic field. Rotation is performed relative to the center of image.

It uses angular motion equation of magnetic dipole in magnetic field to implement such animation.
To vary behaviour (damping, oscillation, responsiveness and so on) set various physical properties.

Use `setPhysical()` to vary physical properties.
Use `rotationUpdate()` to change angle of "magnetic field" at which image should rotate.
