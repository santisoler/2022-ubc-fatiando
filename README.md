# Fatiando a Terra overview for GIF, UBC

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/santisoler/2022-ubc-fatiando/HEAD?filepath=demo.ipynb)

Talk given to the Geophysical Inversion Facility (GIF), EOAS, UBC in August
2022 to introduce the Fatiando a Terra project.

| | Info |
|--:|:------|
| Slides | https://www.santisoler.com/2022-ubc-fatiando |
| Demo notebook | https://mybinder.org/v2/gh/santisoler/2022-ubc-fatiando/HEAD?filepath=demo.ipynb |


## Abstract

The Fatiando a Terra project (https://www.fatiando.org) is a collection of
open-source Python libraries for geophysics which cover a range of
functionalities, from data download and processing to modeling and inversion.
In this opportunity we will present the two libraries that are focused on
potential fields: Harmonica and Boule. Boule implements reference ellipsoids
(including oblate ellipsoids, spheres, and soon triaxial ellipsoids),
conversions between ellipsoidal and geocentric spherical coordinates, and
normal gravity calculations. The latter are performed using analytical
expressions for gravity fields at any point outside of the ellipsoid. Harmonica
provides tools for processing, forward modelling, and inversion of gravity and
magnetic data. We will demonstrate its use to compute Bouguer gravity
disturbances by forward modelling the topography with prisms, removing a 2nd
order regional trend, and interpolating it onto a regular grid at a constant
height using the equivalent layer technique. Both libraries are still evolving
as we continue to refine their goals and scopes. We invite everyone to get
involved in the development, whether it's through coding, writing
documentation, or giving feedback.


## Find out more

Check the Fatiando a Terra website: https://www.fatiando.org


## Attributions

This talk and the slides are based on the _Fatiando a Terra: Open-source tools
for geophysics_ talk given to the Geophysical Society of Huston (GSH) in 2021
by Leonardo Uieda, Santiago Soler and Agustina Pesce. The content of the talk
can be found in https://github.com/fatiando/2021-gsh/ and it's released under
a CC-BY 4.0 License.


## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img
alt="Creative Commons License" style="border-width:0"
src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br>
This content is licensed under a <a rel="license"
href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution
4.0 International License</a>.
