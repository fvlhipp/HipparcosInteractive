<h4 id=intrumModel> The instrument model calibrations </h4>

[1]: ../CalibrationAstr.md
[2]: Images/CaptureGridScale.png "Grid scale evolution"
[3]: Images/CaptureBAEvol.png "Basic angle evolution"

The instrument calibrations represent a main element in the transformation from coordinates in the field of view to coordinates on the sky. The evolution of the coefficients reflects the changes that took place in the telescope and the measures taken to correct the focus. Both effects are seen in the chart below, which is for the along-scan scale corrections.

![Grid scale evolution][2]

Each graph, except for the one showing the basic-angle evolution, has two components. The chart on top shows the mean effect over the two fields of view, the bottom chart shows the difference between the two fields.

![basic angle evolution][3]

The basic angle evolution is shown relative to the reference value of 58 degrees and 31 arcsec. It has been solved as a parameter in the attitude reconstruction, and the error on the determination is generally of order 0.05 mas.
 
The third-order terms as well as the chromaticity have been determined before the final iteration steps and since then fitted with appropriate functions, allowing for discontinuities at thruster firings. 

[Back][1]