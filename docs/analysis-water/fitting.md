# Fitting of effective factors

For each event of MC, the number of photon will be multiplied with a factor then filled into the npe histograms. A $\chi^2$ function is 
created to evaluate the difference of data and MC(npe histograms).
currently,the $\chi^2$ used in fitting is: 
 $$\chi^2=\sum_{i}(\frac{\sum_{j}(Q_{i}\times N_{ij}^{MC}-N_{ij}^{data})}{\sigma_{ij}})^2
$$
where $Q_{i}$ is the calibration factor of $i$th PMT, $N_{ij}$is number of pe in the $j$th bin of 
$i$th PMT ,$\sigma_{ij}$ is the uncertainty of corresponding $N_{pe}$.
************

## no events selection 
if do not select data, just use the Hodoscope trigger events and corresponding MC resultsa.<br>
50 bins in total,fitting results:

| pmt | 0  | 1 | 2  | 3  |4|5|6|7|
|-----|----|----|---|---|---|---|---|---|
| cf  | 1.08 | 0.92 |.46   |.78   |.74| 1.75|1.06|0.86|

<!-----  In the first several bins, the data have more counts than MC.  ---->
<p align="center">
<img src="califigs/PMTnperes0PMTnpedata190929-01.svg" width="900" />
<img src="califigs/PMTnperes1PMTnpedata190929-01.svg" width="900" />
<img src="califigs/PMTnperes2PMTnpedata190929-01.svg" width="900" />
<img src="califigs/PMTnperes3PMTnpedata190929-01.svg" width="900" />
<img src="califigs/PMTnperes4PMTnpedata190929-01.svg" width="900" />
<img src="califigs/PMTnperes5PMTnpedata190929-01.svg" width="900" />
<img src="califigs/PMTnperes6PMTnpedata190929-01.svg" width="900" />
<img src="califigs/PMTnperes7PMTnpedata190929-01.svg" width="900" />
</p>

## about  the problem of chi^2
when I scan the parameter "effective factor" of each PMT, the $\chi^2$ value is not as smooth as expected.
<p align="center">
<img src="califigs/chi2_0PMTnpedata190929-01.png" width="900" />
<img src="califigs/chi2_1PMTnpedata190929-01.png" width="900" />
<img src="califigs/chi2_2PMTnpedata190929-01.png" width="900" />
<img src="califigs/chi2_3PMTnpedata190929-01.png" width="900" />
<img src="califigs/chi2_4PMTnpedata190929-01.png" width="900" />
<img src="califigs/chi2_5PMTnpedata190929-01.png" width="900" />
<img src="califigs/chi2_6PMTnpedata190929-01.png" width="900" />
<img src="califigs/chi2_7PMTnpedata190929-01.png" width="900" />
</p>
