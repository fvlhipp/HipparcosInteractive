<h2 id=reanalyze> The re-analyze window </h2>
[fig53]: Images/CaptureReAnalyze.png "Fig.53, re-analyze tab0"
[fig54]: Images/CaptureBeta5Hip25.png "Fig.54, bet5 for Hip25"
[2a]: http://adsabs.harvard.edu/abs/2007ASSL..350.....V
[1]: AstromDetail.md

![The re-analyze window][fig53]

The re-analyze window is still partly under development. The intention is that it will provide an interactive medium to perform double-star solutions by optimizing differential and astrometric parameters. A new differential solution for double star systems can be obtained, as is shown in the figure above for the system HIP 70, 71 (CCDM 00008+3647). Similarly, a new astrometric solution can be obtained with respect to the new or the old differential parameters. Under development is the combined solution, in which the astrometric and differential parameters are solved together in a Maximum Likelihood solution. The optimum differential solution, as obtained in isolation, often leads to a much deteriorated astrometric solution, and should not as such be used.

![beta5Hip25][fig54]

The different tabs of the **re-analyze** window show the characteristics of the second harmonic in the signal modulation as a function of the orientation of the scan, which is, for narrow binaries, the data used to derive the differential parameters. In most cases there is only very limited coverage over the orientation angle &phi; of the data, which can lead to distorted solutions for the differential parameters if solved on their own. An example, for HIP25 (CCDM 00003-4417) is shown above. For more details see [Hipparcos, the new reduction][2a], Chapter 4 for more detail.

[Back][1]

