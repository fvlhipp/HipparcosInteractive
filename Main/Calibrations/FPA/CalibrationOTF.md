<h4 id=otf> The optical transfer function calibration </h4>

[1]: Images/CaptureOTF.png "Optical transfer function"
[2]: ../CalibrationFPA.md

![otf][1]

The optical transfer function describes the relations between the normalized phase difference and amplitude ratio of the first and second harmonics in the modulated signal. The amplitude ratio is given by &beta;4, the phase difference by &beta;5. The expectation value for &beta;4 is 1 and for &beta;5 is zero. The calibration model describes the corrections with respect to these expectation values.

The calibration model describes the corrections to the expectation values as a third order polynomial in position coordinates (*w* along scan, *z* across scan), up to second order in colour-index dependence, and the linear combinations between colour index and position coordinates (see the tabs in the figure above).

[Back][2]
