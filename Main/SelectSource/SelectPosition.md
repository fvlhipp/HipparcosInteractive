<h4 id="selectbyposition"> Select by position </h4>
[fig05]: Images/CaptureSelectPosition.png "Fig.5, Select by position"
[1]: SelectHip.md
[2]: ../SelectSource.md
 

![Select by position][fig05]

The selection on coordinates requires the specification of the coordinate system (ICRS, B1950, Ecliptic or Galactic), the coordinates (decimal degrees or hexadecimal) and the epoch. Coordinates are transformed to the Hipparcos epoch and equinox, and compared. The identifier of the source nearest to the requested position, but within 1 arcmin, will be returned. If no source was found, the identifier will be -1, and recognized as not being a Hipparcos entry. This information is used to activate the [Selected HIP][1] panel.

[Back][2]

