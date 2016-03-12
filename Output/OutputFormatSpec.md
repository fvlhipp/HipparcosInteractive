<h3 id="formats"> ASCII data formats </h3>
[1]: ../OutputOptions.md

<table style="width:40%">
	<caption>Data formats identifiers</caption>
	<tr>
		<th>Name</th>
		<th>Char.Spaces</th>
		<th>Units</th>
	</tr>
	<tr>
		<td>HIP</td>
		<td>6</td>
		<td>Int</td>
	</tr>
	<tr>
		<td>HD</td>
		<td>6</td>
		<td>Int</td>
	</tr>
	<tr>
		<td>HR</td>
		<td>4</td>
		<td>Int</td>
	</tr>
	<tr>
		<td>Bayer/Flamsteed</td>
		<td>11</td>
		<td>String</td>
	</tr>
	<tr>
		<td>Common Name</td>
		<td>16</td>
		<td>String</td>
	</tr>
	<tr>
		<td>Variab.name</td>
		<td>11</td>
		<td>String</td>
	</tr>
	<tr>
		<td>CCDM</td>
		<td>5,5</td>
		<td>Int,Int</td>
	</tr>
</table>
<table style="width:45%">
	<caption>Data formats astrometry</caption>
	<tr>
		<th>Name</th>
		<th>Char.Spaces</th>
		<th>Units</th>
	</tr>
	<tr>
		<td>&alpha;</td>
		<td>11.6</td>
		<td>Double,degrees</td>
	</tr>
	<tr>
		<td>&delta;</td>
		<td>11.6</td>
		<td>Double,degrees</td>
	</tr>
	<tr>
		<td>&mu;<sub>&alpha;*</sub></td>
		<td>9.2</td>
		<td>Double,mas yr<sup>-1</sup></td>
	</tr>
	<tr>
		<td>&mu;<sub>&delta;</sub></td>
		<td>9.2</td>
		<td>Double,mas yr<sup>-1</sup></td>
	</tr>
	<tr>
		<td>&piv;</sub></td>
		<td>7.2</td>
		<td>Double,mas</td>
	</tr>
	<tr>
		<td>&sigma;&mu;<sub>&alpha;*</sub></td>
		<td>6.2</td>
		<td>Double,mas yr<sup>-1</sup></td>
	</tr>
	<tr>
		<td>&sigma;&mu;<sub>&delta;</sub></td>
		<td>6.2</td>
		<td>Double,mas yr<sup>-1</sup></td>
	</tr>
	<tr>
		<td>&sigma;&piv;</sub></td>
		<td>6.2</td>
		<td>Double,mas</td>
	</tr>
</table>
</table>
<table style="width:40%">
	<caption>Data formats space coordinates</caption>
	<tr>
		<th>Name</th>
		<th>Char.Spaces</th>
		<th>Units</th>
	</tr>
	<tr>
		<td>X</td>
		<td>6.3</td>
		<td>Double,kpc</td>
	</tr>
	<tr>
		<td>Y</td>
		<td>6.3</td>
		<td>Double,kpc</td>
	</tr>
	<tr>
		<td>Z</td>
		<td>6.3</td>
		<td>Double,kpc</td>
	</tr>
	<tr>
		<td>u</td>
		<td>6.1</td>
		<td>Double,km s<sup>-1</sup></td>
	</tr>
	<tr>
		<td>v</td>
		<td>6.1</td>
		<td>Double,km s<sup>-1</sup></td>
	</tr>
	<tr>
		<td>w</td>
		<td>6.1</td>
		<td>Double,km s<sup>-1</sup></td>
	</tr>
</table>
</table>
<table style="width:40%">
	<caption>Data formats flux values</caption>
	<tr>
		<th>Name</th>
		<th>Char.Spaces</th>
		<th>Units</th>
	</tr>
	<tr>
		<td>Obs.Hp</td>
		<td>6.3</td>
		<td>Double,magn</td>
	</tr>
	<tr>
		<td>Abs.Hp</td>
		<td>6.3</td>
		<td>Double,magn</td>
	</tr>
	<tr>
		<td>&sigma;Abs.Hp</td>
		<td>6.3</td>
		<td>Double,magn</td>
	</tr>
	<tr>
		<td>Abs.V</td>
		<td>6.3</td>
		<td>Double,magn</td>
	</tr>
	<tr>
		<td>Scat.Hp</td>
		<td>6.3</td>
		<td>Double,magn</td>
	</tr>
	<tr>
		<td>Var.Type</td>
		<td>1</td>
		<td>String</td>
	</tr>
</table>
<table style="width:40%">
	<caption>Data formats colour values</caption>
	<tr>
		<th>Name</th>
		<th>Char.Spaces</th>
		<th>Units</th>
	</tr>
	<tr>
		<td>(B-V)</td>
		<td>6.3</td>
		<td>Double,magn</td>
	</tr>
	<tr>
		<td>(B-V)<sub>T</sub></td>
		<td>6.3</td>
		<td>Double,magn</td>
	</tr>
	<tr>
		<td>(V-I)</sub></td>
		<td>6.3</td>
		<td>Double,magn</td>
	</tr>
	<tr>
		<td>Spectrum</sub></td>
		<td>12</td>
		<td>String</td>
	</tr>
</table>
<table style="width:40%">
	<caption>Data formats variability</caption>
	<tr>
		<th>Name</th>
		<th>Char.Spaces</th>
		<th>Units</th>
	</tr>
	<tr>
		<td>Variab.Type</td>
		<td>6</td>
		<td>String</td>
	</tr>
	<tr>
		<td>Variab.Per</td>
		<td>6.2</td>
		<td>Double,days</td>
	</tr>
</table>
<table style="width:40%">
	<caption>Data formats miscelaneous</caption>
	<tr>
		<th>Name</th>
		<th>Char.Spaces</th>
		<th>Units</th>
	</tr>
	<tr>
		<td>Rad.Vel.</td>
		<td>6.1</td>
		<td>Double,km s<sup>-1</sup></td>
	</tr>
	<tr>
		<td>Orb.Per.</td>
		<td>7.1</td>
		<td>Double,days</td>
	</tr>
	<tr>
		<td>Separation</td>
		<td>5.1</td>
		<td>Double,arcsec</td>
	</tr>
	<tr>
		<td>Orientation</td>
		<td>6.1</td>
		<td>Double,degrees</td>
	</tr>
	<tr>
		<td>Magn.diff.</td>
		<td>4.1</td>
		<td>Double,magn.</td>
	</tr>
</table>

[Back][1]
