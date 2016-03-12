## Interface Structure ##
[1]: MainWindow.md
[16]: OutputOptions.md
[9]: popupmenu.md
[22]: PdfChart.md
[14]: Main/ListIdentifiers.md
[15]: Main/ListCriteria.md
[26]: Main/Calibrations.md
[12]: Main/Maps.md
[11]: Main/ErrorDistr.md
[10]: Main/Photometry.md
[7]: Main/HRDiagrams.md
[8]: Main/SummaryInfWind.md
[2]: Main/SelectSource.md
[3]: Main/SelectSource/SelectByNumber.md
[4]: Main/SelectSource/SelectSolution.md
[5]: Main/SelectSource/SelectPosition.md
[6]: Main/SelectSource/SelectHip.md
[13]: Main/Calibrations.md
[26]: Main/Calibrations/CalibrationFPA.md
[27]: Main/Calibrations/CalibrationAstr.md
[28]: Main/Calibrations/CalibrationSM.md
[29]: Main/Calibrations/CalibrationMisc.md
[18]: Main/Summary/SummarySourceId.md
[19]: Main/Summary/SummaryAstrom.md
[20]: Main/Summary/SummaryPhotom.md
[21]: Main/Summary/SummaryLightCurve.md
[23]: Main/Summary/AstromDetail.md
[24]: Main/Summary/TychoEpPhot.md
[30]: Main/Summary/ReAnalyze.md
[17]: Main/Summary/HIP110991_info.pdf

- [Main window][1]
	- Main (menu)
		- Start (menu item)
		- Data location (menu item)
		- Close (menu item)
	- [Single stars][2] (tab)
		- [Select by identifier][3] (tab)
		- [Select by solution type][4] (tab)
		- [Select by position][5] (tab)
		- [Get summary information][6] (Button)
			- [Summary information][8] (window)
	- [HR Diagrams][7] (tab)
		- HR Diagram(s) display (widow)
			- Identify (cursor, button)
				- [Summary information][8] (window)
			- Emphasis (button)
				- Select spectra (window)
			- [Popup menu][9]
			- Cursor position (display)
	- [Photometry][10] (tab)
		- Photometric diagram(s) display (window)
			- Identify (cursor, button)
				- [Summary information][8] (window)
			- [Popup menu][9]
			- Cursor position (display)
	- [Error Distributions][11] (tab)
		- Error distributions display (window)
			- Identify (cursor, button)
				- [Summary information][8] (window)
			- [Popup menu][9]
			- Cursor position (display)
	- [Maps][12] (tab)
		- Display map
			- Find constellation
				- Constellations list
			- Identify (cursor, button)
				- [Summary information][8] (button)
			- Move to (Cursor, button)
			- Cursor position (display)
	- [Calibrations][13] (tab) 
 	    - [Focal-plane assembly related][26] (tab)
	    - [Attitude related][27] (tab)
	    - [Star mapper related][28] (tab)
	    - [Miscellaneous][29] (tab)	    
    - [List by identifiers][14] (menu)
		- By Hipparcos number
			- [Output Contents dialogue][15]
		- By HD number
			- [Output Contents dialogue][15]
		- By HR number
			- [Output Contents dialogue][15]
	- [List By selection criteria][15] (menu)
		- Selection criteria (window)
			- [Output Contents dialogue][15]
- [Summary information][8] (window)
	- [Identifiers][18] (tab)
	- [Astrometric][19] summary (tab)
		- Orbital binaries
		- Orbit (tab, when available)
		- Double and multiple stars
		- [Detailed information][23] (window)
			- Epoch dependencies (tab)
			- Parallax factor dependencies (tab)
			- Error dependencies (tab)
			- Scan-direction dependencies (tab)
			- Parallax factor-scan direction correlations (tab)
			- [PDF of chart][21] (button, applies to active tab)
			- Re-analyze astrometric solution (button)
				- [Re-analyze display][30] (window)
					- (Available options depend on solution type)
	- [Photometric summary][20] (tab)
		- Ground-based photometry (Button, when availabe))
			- Ground-based photometry (window)
		- Tycho epoch photometry (button, when available)
			- [Tycho epoch photometry][24]
		- Epoch photometry (tab, when available)
	- [Light curve][20] (tab, When relevant, periodic variables)
	- PDF info sheet (button)
	- [PDF of chart][21] (button, applies to active tab)
		- Output file dialogue (window)
- [Output Contents dialogue][15] (window)
	- Identifiers (tab)
	- Astrometry (tab)
	- Photometry (tab)
	- Output format (tab)
	- Other information (tab)
	- Output file (Button)
		- Output file dialogue (window)
- [Chart to pdf dialogue][22] (window)
	- Set file name (button)
	- Set orientation (options)
	- Set paper size (options)
- [Pop-up menu][9] charts (menu)
	- Increase dot size (menu item)
	- Decrease dot size (menu item)
	- Invert abscissa (menu item)
	- Invert ordinate (menu item)
	- Align charts (menu item)
	- [PDF copy][22] (menu item)
		- Chart to pdf dialogue (window)
	- List (menu item)
		- [Selection criteria][15] (window)
	- Toggle colour legend (menu item)
