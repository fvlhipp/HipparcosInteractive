<h3 id="photomsummary"> Photometric Summary </h3>
[fig36]: Images/CaptureSourceInfoPhot.png "Fig.36, Photometric Summary &delta; Cep"
[fig37]: Images/CaptureGBRRLyr.png "Fig.37, Ground-based photometry"
[fig38]: Images/CaptureBinaryStar.png "Fig.38, Epoch photometry binary"
[1]: http://adsabs.harvard.edu/abs/1997ESASP1200.....P
[3]: http://adsabs.harvard.edu/abs/1980VA.....24..141G
[4]: http://cdsads.u-strasbg.fr/abs/1998A%26AS..129..431H
[5]: http://adsabs.harvard.edu/abs/1977A%26A....54..137L
[6]: TychoEpPhot.md
[7]: ../SummaryInfWind.md

![Photometric Summary &delta; Cep][fig36]

The Photometric Summary provides the information on brightness, colours, spectral type and variability. The panel shows the accumulated photometric information as obtained by or for the mission. The source of colour indices and spectral type is also indicated by the single letter following the data. The full explanation of these codes can be found in [SP-1200][1], Volume 1. The reference to where to find more information to these sources also shows as a tooltip when hovering the pointer on the field. For variable stars an additional panel shows the variability information, either as periodic variable, as shown in the Figure above, or as unresolved variable. When Tycho Epoch Photometry is available (applies to 13843 entries), a [button][6] appears through which this can be shown.

<h4 id="groundbased"> Ground-based photometry </h4>
![Ground-based photometry][fig37]

When ground-based photometry is available, this can be shown through a button which is activated in that case, and situated below the summary data. Ground-based photometry has been included from archives of the
[Geneva][3], [Str&#246;mgren][4] and [Walraven][5] photometry. 

<h4 id="epochphotom"> Epoch Photometry </h4>
![Epoch photometry binary][fig38]

For all stars for which epoch photometry is available, this epoch photometry is shown as a chart on a separate tab, marked **Epoch Photometry**. The epoch photometry originates from two sources, the mean flux and the amplitude of the first harmonic in the flux-modulation. The first of these, referred to as H<sub>dc</sub> is potentially the more accurate, but is for faint stars affected by uncertainties in the background subtraction. The second of these, referred to as H<sub>ac</sub> is not affected by background, but has a significantly lower signal to noise ratio. In addition, whenever the image of more than one star was visible within the instantaneous field of view, the amplitude of the first harmonic was reduced relative to the mean flux, depending on the separation of the components, the orientation of the components with respect to the scan direction, and the flux ratio of the components. An example is shown in the figure above. Although in most cases the H<sub>ac</sub> magnitudes are fainter than the H<sub>dc</sub> magnitudes, this is often not the case when separations of around 10 to 15 arcsec are encountered. This indicates different effective instantaneous fields of view for the mean and modulated signals. An example of this is the pair HIP 70 and HIP 71. For the fainter star, HIP 70, the H<sub>ac</sub> magnitudes are all brighter than the H<sub>dc</sub> magnitudes.

[Back][7]
