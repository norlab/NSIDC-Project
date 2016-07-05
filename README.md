<body>
<div id="header">
<h1 style="text-align: center;"><span style="font-weight: 600;"> Analysis of NSIDC Dataset Downloads and Metadata</span></h1>
<h2 style="text-align: center;"><span style="font-weight: 400;">The Relationship Between Extant Metadata and Download Rates of Datasets in the National Snow and Ice Data Center Repository</span></h1>

</div>


<table class="tg">
  <tr>
    <td class="tg-s6z2">Yulia Kolesnikova</td>
    <td class="tg-s6z2">Adam Lathrop<br></td>
    <td class="tg-s6z2">Bree Norlander<br></td>
    <td class="tg-s6z2">An Yan<br></td>
  </tr>
  <tr>
    <td class="tg-s6z2">University of Washington<br></td>
    <td class="tg-s6z2">University of Washington<br></td>
    <td class="tg-s6z2">University of Washington<br></td>
    <td class="tg-s6z2">University of Washington<br></td>
  </tr>
  <tr>
    <td class="tg-s6z2">Information School<br></td>
    <td class="tg-s6z2">Information School<br></td>
    <td class="tg-s6z2">Information School<br></td>
    <td class="tg-s6z2">Information School<br></td>
  </tr>
  <tr>
    <td class="tg-s6z2">kolesy@uw.edu</td>
    <td class="tg-s6z2">adl5@uw.edu</td>
    <td class="tg-s6z2">norlab@uw.edu</td>
    <td class="tg-s6z2">yanan15@uw.edu</td>
  </tr>
</table>
</div>
<div id="abstract">
<h1>Abstract</h1>
There are few research studies that quantitatively analyze metadata elements associated with scientific data reuse. By using metadata and dataset download rates from the National Snow and Ice Data Center, we address whether there are key indicators in data repository metadata that correlate with the download rate of a dataset and whether we can predict data reuse using machine learning techniques. We used the rate of download by unique IP addresses for individual datasets as our dependent variable and as a proxy for data reuse. Our analysis shows that the following metadata elements in NSIDC datasets are positively correlated with download rates: year of citation, number of data formats, number of contributors, number of platforms, number of  spatial coverage areas, number of locations, and number of keywords. Our results are applicable to researchers and professionals working with data and add to the small body of work addressing metadata best practices for increasing discovery of data.
<h2>Keywords</h2>
metadata, data curation, machine learning, data citation, data reuse, data repositories
</div>
<div id="vis">
<h2>Visualizations</h2>

<figure>
    <img src="https://infx575nsidc.files.wordpress.com/2016/05/hist_logdownloaddistribution.jpg" alt="Hist_LogDownloadDistribution"/>
    <figcaption>Log-normal distribution of dataset downloads.</figcaption>
</figure>
<figure>
    <img src="https://infx575nsidc.files.wordpress.com/2016/05/adamtree3.png" alt="AdamTree3"/>
    <figcaption>Decision tree using training data with lowest natural log RMSE (1.29623 ln). Unlabels numeric in each box represents the mean ln of download rates for the given sample (n) of the data. Created with R package RPart version 4.1.10 (Milborrow, 2014) using colors from RColorBrewer version 1.1.2 (Neuwirth, 2011).</figcaption>
</figure>
</div>


<div id="footer">
INFX 575: Data Scaling, Applications and Ethics
</div>
</body>
