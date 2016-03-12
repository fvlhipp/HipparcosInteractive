<h4 id=idtphot> The photometric calibrations </h4>

[1]: ../CalibrationFPA.md
[2]: Images/CaptureIDTPhot.png "idt photometry"
[3]: CalibrationIfov.md
[4]: Images/CaptureCalibrPhotVI.png "IDT photometry VI dependence"
[5]: http://adsabs.harvard.edu/abs/1992A%26A...258..149E
[6]: http://adsabs.harvard.edu/abs/1997ESASP1200.....P

The Hipparcos magnitudes have been derived from the mean flux (H<sub>dc</sub>) and amplitude of the first harmonic (H<sub>ac</sub>) of the stellar image as modulated by the grid and recorded by a photomultiplier for which the sensitive area (the [instantaneous field of view][3]) was directed by an image dissector tube (IDT). The H<sub>ac</sub> photometry was affected by the focus of the telescope, which was evolving and requiring corrections early in the mission. The IDT was sensitive to radiation, causing significant darkening of the IDT optics, and the loss of nearly 50 per cent of the flux towards the end of the mission. This can be observed in the diagram below.

![IDT photometry][2]

Due to the same darkening of the optics, the pass band evolved, which is reflected in the colour-dependencies, as shown below. The zero point for the dependencies represents the reference pass band for the Hipparcos magnitudes.

![IDT photometry VI dependence][4]

The IDT photometry was characterized by a more or less central, circular response feature, which was modelled with radial dependencies, starting with a quadratic term (coefficients RAD2 to RAD7). 

The background had been modelled as good as possible using information from the background as measured with the Star Mapper detectors, and a small overall non-linear correction (the calibrations were done in log(intensity) scale). More details on the photometric calibrations can be found [here][5] and in [SP-1200][6], volume 3.

[Back][1]