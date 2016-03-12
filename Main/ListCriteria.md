## List by selection criteria ##
[fig24]: Images/CaptureAstromSel.png "Fig.24, Astrometric selection criteria"
[fig25]: Images/CaptureSelPosSky.png "Fig.25, Selection position on sky"
[fig26]: Images/CaptureSelPosLimits.png "Fig.26, Selection position limits"
[fig27]: Images/CapturePhotomSel.png "Fig.26, Photometric selection criteria"
[fig28]: Images/CaptureSelVarTypes.png "Fig.27, Variable types selection"
[fig29]: Images/CaptureSpectrSel.png "Fig.29, Spectra selection"
[fig30]: Images/CaptureSelSpectrMask.png "Fig.30, Spectral mask"
[1]: ../MainWindow.md
[2]: ../OutputOptions.md

The fourth list-menu option, **Criteria** leads to a a window with selection options based on astrometric, photometric and spectroscopic criteria.
<h4 id="selectioncrit"> Selection criteria </h4>
![Astrometric selection criteria][fig24]

The astrometric selection criteria use data on the parallaxes, relative and absolute errors, minimum and maximum parallax values, and solution types. These can by either included in, or excluded from, the overall selection. There are in addition three options for selection on position:

- Any position
- Within a radius from a specified reference position
- Within a filed described by coordinate limits

![Selection position on sky][fig25]
![Selection position limits][fig26]

The next tab shows the photometric selection options. The first part of the selection is based on limits in apparent and/or absolute magnitude and in (B-V) or (V-I) colour index. 

![Photometric selection criteria][fig27]

The second part has the option to select on variability types:

![Variable types selection][fig28]

Any combination of types can be selected by using Ctrl and select (left mouse button) on Windows, or Cmnd and select on Mac.

The third tab allows for selection on spectral characteristics, with a resolution on spectral type (main types only) and luminosity class, and the possibility to include various peculiar spectral features.

![Spectra selection][fig29]

The box **Only stars with RV data** can be checked if that is what is required. For spectra selction it is also possible to use a spectral mask:

![Spectral mask][fig30]

This can be used either as an exact mask, i.e. spectra should be exactly the same as the mask, or as a string that should be part of the spectral classification.

Once all selection criteria have been set, the **Apply and Close** button moves the user to the next window, taking the settings on all tabs in the selection window. This activates the [Output Options][2] window.

[Back][1]
