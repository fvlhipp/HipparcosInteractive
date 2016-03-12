<h3 id="astromsumm"> Astrometric Summary </h3>
[fig32]: Images/CaptureSourceInfoAstrom.png "Fig.32, Astrometric Summary"
[fig33]: Images/CaptureSourceInfoOrbit2.png "Fig.33, Orbit info window"
[fig34]: Images/CaptureOrbit1349.png "Fig.34, Orbit Hip 1349"
[fig35]: Images/CaptureTrapezium.png "Fig.35, The Trapezium cluster"
[1]: ../SummaryInfWind.md
[2]: AstromDetail.md

![Astrometric Summary][fig32]

The astrometric data tab shows the astrometric solutions in the 1997 and the 2007 reductions, including details on the solution applied. At this stage only the results for the basic 5 astrometric parameters is shown:position, parallax and proper motion. Details of the astrometric solution in the 2007 reduction are shown by clicking the **Details** button. This will show the full [solution details][2] as well as the distribution of the data with respect to epoch, parallax factor and scan direction.
<h4 id="orbitalbinary"> Orbital binaries </h4>
![Orbit Info window][fig33]

When a star is known to be part of an orbital double system for which the orbital solution has been applied prior to the astrometric parameter determination (solution type 75), the orbital parameters that were implemented are displayed with the astrometric solution. 
<h4 id="orbitexample"> The orbit chart </h4>
![Orbit Hip 1349][fig34]

Also shown on a separate tab is the orbit with the positions on the orbit when Hipparcos observations were obtained. These are not the observations themselves, as these are one-dimensional and would show as lines associated with the observed transit time. A mechanism to re-evaluate the astrometric solution with a different set of orbital parameters is still under development.
<h4 id="doublemultiple"> Resolved double and multiple stars </h4>
![The Trapezium cluster][fig35]

This section concerns observations for which more than one image is visible within the instantaneous field of view, an area of roughly 15 arcsec diameter. An additional panel on the Astrometric Summary tab displays automatically the double star information. There are two classes of object here: those for which individual integrations were obtained for each (or some in case of multiple stars) components, and those for which all data was contained in single integrations. Both cases are shown in the Figure above for the Trapezium cluster in Orion. The components B and D are too close together to be separated in the instantaneous field of view, while components A and C are well enough separated. The data provided are the separations, orientation angles and individual magnitudes as used in the processing of the astrometric data.

[Back][1]
