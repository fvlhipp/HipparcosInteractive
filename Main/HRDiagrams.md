<h3 id="hrdiagram"> HR Diagrams </h3>
[fig09]: Images/CaptureHRDiagrams.png "Fig.9, Create HR diagrams"
[fig10]: Images/CaptureHRDiagramCharts.png "Fig.10, HR diagram charts"
[fig11]: Images/CaptureHRDiagrSpectr.png "Fig.11, HR diagram spectral types"
[fig12]: Images/CaptureSelectSpectra.png "Fig.12, "Spectra selection"
[fig13]: Images/CaptureHRDiagrEmphas.png "Fig.13, "Emphasis on A stars"
[1]: ../MainWindow.md
[2]: SummaryInfWind.md
[3]: ../ChartFacilities.md
[4]: ../popupmenu.md

![HR diagrams][fig09]

The creation of HR diagrams follows three main steps:

1. selection of the relative accuracy of the parallaxes, where it should be considered that relative errors greater than 10 per cent will lead to asymmetric error distributions in the absolute magnitudes, and an error of 10 per cent is approximately equivalent to a 0.1 magnitude noise on the absolute magnitudes;
2. selection of the abscissa and ordinate of the charts, where the default settings (B-V) or (V-I) against Hp are producing the more useful diagrams;
3. colour coding; here each box ticked will produce a chart.

Once all selections have been made, the button **Show graphs** is used to display the charts. This will also fill in the number of selected stars in the lower panel of the figure shown above.

<h4 id="hrdiagrcharts"> The HR diagram charts </h4>

![HR diagram charts][fig10]

The figure above shows the display created by selecting the 18489 stars with relative errors on the parallaxes less than 7 per cent, selecting (B-V) for the abscissa and Hp for the ordinate, and colour coding according to spectral type, luminosity type, and transverse velocity. The latter is calculated from the proper motion and parallax values, and is statistically an indication of the age of groups of stars. In the section on [chart facilities][3] is described how to use jFreeChart facilities and the [Pop-up menu][4] to examine these charts in much more detail. Any data point is these charts can be linked to, and identified with, an entry in the Hipparcos catalogue by moving the cross wires with the cursor to a data point, and click of the left mouse button. The cross wires now remain fixed, and the **Identify** button is used to find the Hipparcos number to which the data point belongs, and to display the [Summary information][2] for this catalogue entry. 

<h4 id="emphasis"> The emphasis dialogue </h4>

![HR diagram spectra][fig11]

The HR diagram with colour coding according to spectral type offers one additional feature, the possibility to show the distribution of points selected for specific spectral types and luminosity classes. This is done through the **Emphasis** button, which activates the selection window shown below.

![Spectra selection][fig12]

In the example use shown above all A stars of luminosity classes IV/V to V/VI are selected. Other selections can be done using a specific mask to filter out spectral types. The selection boxes are not mutually exclusive, and can be combined in any combination, except for the **All** boxes, the activation of which will wipe out any other selection in the same column, while at the same time the **All** box is cleared when an other box in the same column is selected. The **Apply** button activates a standard colour-selection dialogue, for selecting the colour assigned to the selected data points. A dark colour is advisable for this purpose. Once the colour has been selected, the HR diagram display is updated with the new colour assigned to the selected stars.

![Emphasis on A stars][fig13]

In the image above the jFreeChart facilities were used to focus in on the A stars, while the option to increase the dot size was used from the [Pop-up menu][4] to get a clearer few of the distributions. The purple points are in this case the stars selected based on the criteria used in the selection window.

[Back][1]
