# A GMRT survey of regions towards the Taurus Molecular Cloud at 323 and 608 MHz

<p>This survey is the first in a series of surveys of star forming regions, taken at 325 and 610 MHz with the Giant Metrewave Radio Telescope (<a href="http://www.gmrt.ncra.tifr.res.in/">GMRT</a>). Full details of the observations, data reduction, images and source catalogue can be found in <i>Ainsworth R. E., Coughlan C. P., Green D. A., Scaife A. M. M., Ray T. P., 2016, MNRAS, 462, 2904 (<a href="http://adsabs.harvard.edu/abs/2016MNRAS.462.2904A">paper</a>)</i>. </p>

<h2>Summary</h2>

<p>We present observations of three active sites of star formation in the Taurus Molecular Cloud complex taken at 323 and 608 MHz (90 and 50 cm, respectively) with the Giant Metrewave Radio Telescope (GMRT). Three pointings were observed as part of a pathfinder project, targeted at the young stellar objects (YSOs) L1551 IRS 5, T Tau and DG Tau (the results for these target sources were presented in a previous paper). In this paper, we search for other YSOs and present a survey comprising of all three fields; a by-product of the large instantaneous field of view of the GMRT. The resolution of the survey is of order 10&#8243; and the best rms noise at the centre of each pointing is of order 100 &#956;Jy at 323 MHz and 50 &#956;Jy at 608 MHz. We present a catalogue of 1815 and 687 field sources detected above 5&#963; at 323 and 608 MHz, respectively. A total of 440 sources were detected at both frequencies, corresponding to a total unique source count of 2062 sources. We compare the results with previous surveys and showcase a sample of extended extragalactic objects. Although no further YSOs were detected in addition to the target YSOs based on our source finding criteria, these data can be useful for targeted manual searches, studies of radio galaxies or to assist in the calibration of future observations with the Low Frequency Array (LOFAR) towards these regions.</p>

<HR WIDTH="60%">

<p>We provide image files in FITS format for each field at each frequency at both native and re-imaged resolutions with primary beam correction applied (12 FITS images in total). The <b>*_catalogue.FITS</b> files (first column) were used to create the source catalogue presented in this work, each with an image cell size of 1.5 arcsec and CLEAN restoring beam as listed in the <a href="http://adsabs.harvard.edu/abs/2016MNRAS.462.2904A">paper</a>. The <b>*_native.FITS</b> files (second column) are the original image files with the native resolution used to detect the target sources, the results of which were presented in <a href="http://adsabs.harvard.edu/abs/2016MNRAS.459.1248A">Ainsworth et al. (2016)</a>. </p>

<p>The final source catalogue is made available in a machine-readable format as part of the data release (<b>GMRT-TAU.dat</b>). In addition, a table providing all the parameter outputs from PyBDSM is provided (<b>GMRT-TAU_PyBDSM.csv</b>), see the <a href="http://www.astron.nl/citt/pybdsm/">online documentation</a> for a full description. 

A series of python scripts were developed to create the final catalogue and diagnostic plots from the PyBDSM catalogue files for each individual field and frequency. These files are available and can be used to re-constitute the catalogue at any time. <b>make_catalog.py</b> takes the PyBDSM output for a single field at both frequencies and generates a final catalogue,  complete with spectral indices, source matching between frequencies, and comparisons with other surveys. It outputs these results in a LaTeX format that can then be combined with results from additional fields to make the final GMRT-TAU catalogue. Additional files are also created which can read by <b>make_plots.py</b> to generate the diagnostic plots presented in this paper. Finally, a <b>*.csv</b> file is created which contains all of the information in the latex file, in addition to default PyBDSM columns and additional columns used for internal calculation by <b>make_catalog.py</b>, but which may be of use in further study.

<p> The image files, source catalogues and scripts are available through links in the table below. If you use the data from this webpage, please cite the <a href="http://adsabs.harvard.edu/abs/2016MNRAS.462.2904A">paper</a>.</p>

<center><table border="1" cellpadding="5" cellspacing="0">
  <tbody>
    <tr>
      <th><center>Catalogue resolution FITS Images</center></th>
      <th><center> Native resolution FITS Images</center></th>
      <th><center> CSV source catalogue and PyBDSM output catalogue</center></th>
      <th><center> Scripts used to generate catalogue and diagnostic plots</center></th>
    </tr>
    <tr align="center">
      <td><a href="GMRT-TAU_catalogue/L1551_323MHz_catalogue.FITS">L1551_323MHz_catalogue.FITS</a></td>
      <td><a href="GMRT-TAU_catalogue/L1551_323MHz_native.FITS">L1551_323MHz_native.FITS</a></td>
      <td><a href="GMRT-TAU_catalogue/GMRT-TAU.pdf">GMRT-TAU.pdf</a></td>
      <td><a href="GMRT-TAU_catalogue/make_catalogue.py">make_catalogue.py</a></td>
    </tr>
    <tr align="center">
      <td><a href="GMRT-TAU_catalogue/L1551_608MHz_catalogue.FITS">L1551_608MHz_catalogue.FITS</a></td>
      <td><a href="GMRT-TAU_catalogue/L1551_608MHz_native.FITS">L1551_608MHz_native.FITS</a></td>
      <td><a href="GMRT-TAU_catalogue/GMRT-TAU.dat">GMRT-TAU.dat</a></td>
      <td><a href="GMRT-TAU_catalogue/make_plots.py">make_plots.py</a></td>
    </tr>
    <tr align="center">
      <td><a href="GMRT-TAU_catalogue/TTau_323MHz_catalogue.FITS">TTau_323MHz_catalogue.FITS</a></td>
      <td><a href="GMRT-TAU_catalogue/TTau_323MHz_native.FITS">TTau_323MHz_native.FITS</a></td>
      <td><a href="GMRT-TAU_catalogue/ReadMe">ReadMe</a></td>
      <td></td>
    </tr>
    <tr align="center">
      <td><a href="GMRT-TAU_catalogue/TTau_608MHz_catalogue.FITS">TTau_608MHz_catalogue.FITS</a></td>
      <td><a href="GMRT-TAU_catalogue/TTau_608MHz_native.FITS">TTau_608MHz_native.FITS</a></td>
      <td><a href="GMRT-TAU_catalogue/GMRT-TAU_PyBDSM.csv">GMRT-TAU_PyBDSM.csv</a></td>
      <td></td>
    </tr>
    <tr align="center">
      <td><a href="GMRT-TAU_catalogue/DGTau_323MHz_catalogue.FITS">DGTau_323MHz_catalogue.FITS</a></td>
      <td><a href="GMRT-TAU_catalogue/DGTau_323MHz_native.FITS">DGTau_323MHz_native.FITS</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr align="center">
      <td><a href="GMRT-TAU_catalogue/DGTau_608MHz_catalogue.FITS">DGTau_608MHz_catalogue.FITS</a></td>
      <td><a href="GMRT-TAU_catalogue/DGTau_608MHz_native.FITS">DGTau_608MHz_native.FITS</a></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table></center>
