<h3 id="errordistr"> Error distributions </h3>
[fig17]: Images/CaptureErrorDist.png "Fig.17, Error distributions"
[fig18]: Images/CaptureParError.png "Fig18, Parallax errors"
[1]: ../MainWindow.md
[2]: ../popupmenu.md

![Error distributions][fig17]

The standard errors on the astrometric and photometric parameters, as determined by the Hipparcos data reductions, are displayed as a function of stellar magnitude. This can be done either colour coded with the ecliptic latitude of the source, or monochrome, in a colour selected by the user. The graphs to be shown are selected by means of the check boxes, and either astrometric or photometric graphs are shown. As the astrometric errors can be affected by duplicity, there is the option to include or not non-single stars. For the photometry there is the additional option of a so-called normalized graph, where the errors are normalized based on a Poisson error proportional to the flux of a star. The button Show graphs will activate the **Error Distributions Display** window.
<h4 id="errordisplay"> The error Display Window </h4>
![Parallax errors][fig18]
The colour coding is based on the ecliptic latitude of the sources, from close to the ecliptic (red) to near the ecliptic pole (blue). It shows the effects of the scanning law used by Hipparcos on the errors for the parallaxes. For proper motions and positions these dependencies are significantly different. The differences between the 1997 and 2007 reduction results can also be observed this way. As in other charts, the cross-wires and left mouse button can be used to locate and identify each data point. Pushing the **Identify** button will show the [Summary information](#sourceinfo) window for the identified source. Similarly, the [Pop-up menu][2] provides various means to manipulate and print the chart.

[Back][1]
