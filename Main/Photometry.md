<h3 id="colourcolour"> Colour-colour diagrams, ground-based photometry </h3>
[fig14]: Images/CapturePhotomInit.png "Fig.14, Ground-based photometry"
[fig15]: Images/CapturePhotIndices.png "Fig.15, "Photometric indices selection"
[fig16]: Images/CaptureColColDiagram.png "Fig.16, Colour-colour diagram"
[1]: ../MainWindow.md
[2]: SummaryInfWind.md
[3]: http://adsabs.harvard.edu/abs/1980VA.....24..141G
[4]: http://cdsads.u-strasbg.fr/abs/1998A%26AS..129..431H
[5]: http://adsabs.harvard.edu/abs/1977A%26A....54..137L
[6]: ../popupmenu.md

![Ground-based photometry][fig14]

This section provides methods to combine large volumes of ground-based photometry with Hipparcos astrometric as well as spectroscopic data. Currently four data sets are available:

1. [Geneva] [3] photometry archive, as provided by Laurent Eyer
2. [Stromgren] [4] photometry, as extracted from Vizier
3. [H&beta;] [4] photometry, as extracted from Vizier
4. [Walraven VBLUW] [5] photometry archive, as provided by Jan Lub

These archives can be used singly or combined. When combined, only data for stars with photometric measurements in all selected systems will be shown. The  *Help* label shows, by hovering over it, some brief instructions.

The first selection stage selects the photometric systems and sets the limits on the relative and absolute parallax accuracies. The **Continue** button then shows the second selection panel:

![Photometric indices selection][fig15]

From the drop-box under **Index 1** the abscissa for a chart is selected, and similarly under **Index 2** the ordinate. The different indices as available are preceded by G, S, or W, depending on the photometric system. The colour coding can be by absolute magnitude, spectral type, luminosity class, or any of the available colour indices. The colour indices made available include often-used combinations, such as the so-called de-reddened Walraven indices, as indicated by square brackets. For each selection made, push the **Add Chart** button. When all selections have been made, push the **Show Charts** button. This will show the photometry window.
<h4 id="photomdiagr"> Photometric Diagrams display </h4>
![Colour-colour diagram][fig16]

The image shows the Geneva photometry two colour diagram (U-B1) against (V1-B), colour coded with the absolute magnitudes of the stars, ranging from Blue for bright to red for faint. Clearly visible is the separation between dwarfs and giants among the red stars. as well as the dependence on surface gravity for F-type stars (V1-B between 1.5 and 0.75). The axes of a chart can be inverted each through the [Pop-up menu][6]. When the same chart is produced for different dependencies, the **align** menu option in the [Pop-up menu][6] can be used to synchronize zoom-in on the different charts. The cross-wires and left mouse button can be used to locate and identify each data point. Pushing the **Identify** button will show the [Summary information][2] window for the identified source.

[Back][1]
