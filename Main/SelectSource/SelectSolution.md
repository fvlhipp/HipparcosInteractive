<h4 id="selectsolution"> Select by solution </h4>
[fig04]: Images/CaptureSelectSolution.png "Fig.4, select on solution type"
[1]: SelectHip.md
[2]: ../SelectSource.md

![Select on solution type][fig04]

Selection on solution type is intended to give easy access to any solution that required more than a simple single-source five-parameter astrometric model to fit the data. In most cases this is due to image and/or orbital disturbance caused by one or more companions. At least one additional source of disturbance is recognised, and is specific for super giants, where the size of the star is compatible with the diameter of the Earth orbit, and where due to the rather loose structure of the star there are significant brightness variations over the stellar surface. This will create positional noise that can be significant compared to the positional variations as a result of the parallax. These objects will be referred to as large spotted stars.
The following solution types are available for selection:

- stochastic solutions, where additional noise is observed in the data using 5, 7 or 9 parameter solutions, but no model was found to improve the fitting; the additional noise could represent unresolved orbital motions or be the result of large spotted stars; if the source is known to be part of a double or multiple orbital system, then this is indicated with the identifier;
- 7-parameter solutions; these refer, where significant, mostly to probable long-period orbital motions; the additional two parameters represent the acceleration in the proper motion;
- 9-parameter solutions; this is a more extreme case of the 7-parameter solutions; if real, they can represent shorter period orbital solutions;
- variability-induced motion (VIM): this group represents variable stars with a faint companion, of which the effect on the astrometry depends on the brightness of the primary star;
- orbital motion; two cases are distinguished here, solution type 75, where the orbital parameters, as specified on the astrometric summary page, have been taken into account before the astrometric solution (indicated by solution type 75); the second type concerns known long-period orbital binaries, where the orbit has not been taken into account for the solution (indicated by solution type 1, stochastic, or other codes implying further complications;
- double or multiple stars, for which the components are observed together within the instantaneous field of view; solutions apply to the primary;
- double and variable; as double stars, but with the primary being variable;
- narrow binaries, where the solution applies to the photo centre;
- two-windows; wider binary systems, where each component was observed separately, but still close enough to cause some disturbance on the other component;
- variable faint component; binary system where the secondary is assumed to be variable (only one rather doubtful case).

Each entry shows all candidates within the Hipparcos catalogue that fulfil the selection criterion. Some stars can appear under more than one category, such as stochastic and orbital, binary and orbital.

The button **Get HIP** produces in each case either the relevant Hipparcos catalogue number (or a message that the requested number is not contained in the Hipparcos catalogue) through the panel [Selected HIP][1].

[Back][2]
