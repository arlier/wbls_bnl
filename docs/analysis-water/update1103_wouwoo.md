
| 1st and last bin | 0  | 1 | 2  | 3  |4|5|6|7|
|-----|----|----|---|---|---|---|---|---|
| calibration factor wouwoo | 0.904 | 0.702 |0.475   |0.858   |1.608| 1.638|1.112|0.84|
| calibration factor  wouwo| 0.904 | 0.702 |0.475   |0.858   |1.608| 1.638|1.112|0.84|
| calibration factor  wuwoo| 0.904 | 0.697 |0.467   |0.856   |1.632| 1.638|1.112|0.84|
| calibration factor wuwo | 0.904 | 0.697 |0.467   |0.856   |1.632| 1.638|1.112|0.84|
|  minimum $\chi^2$ wouwoo  | 119.0 | 254.3 |1452.7   |381.6   |2214.2| 1535.9|148.0|128.5|
|  minimum $\chi^2$ wouwo  | 125.8 | 259.9 |1458.7   |382.6   |2251.2| 1554.9|149.7|129.4|
|  minimum $\chi^2$ wuwoo  | 153.1 | 321.6 |2390.5   |416.9   |2407.9| 1662.1|174.2|165.9|
|  minimum $\chi^2$ wuwo  | 159.9 | 326.9 |2396.5   |417.9   |2444.9| 1681.1|176.0|166.7|

## fitting chi2 without first and without last bin.

water attenuation length=20m;bin width=1p.e/bin;
$r=10$ is the ratio of total event number from MC and data, each event in MC is multiplied by the calibration factor $f$ then filled into the MC histogram. After scaling the MC histogram with $r$, the definition of $\chi^2$
$$
\chi^2 =\sum_{n=1}^{n=max\_bin-1}(\frac{N_{n,data}-N_{n,MC}}{\sigma_{n}})^2
$$
where $f$ is the calibration factor, max\_bin is the bin converted by all the bins in orignal histogram with count less than10;$N_{n,data}$ is the count of nth bin in data histogram, $N_{n,MC}$ is the nth bin in MC histogram. $\sigma_{n}$ is defined as $\sigma_{n}=\sqrt{N_{MC}/r^2+N_{data}}$.

| wo 1stbin&wo last bin | 0  | 1 | 2  | 3  |4|5|6|7|
|-----|----|----|---|---|---|---|---|---|
| calibration factor  | 0.904 | 0.702 |0.475   |0.858   |1.608| 1.638|1.112|0.84|
|  minimum $\chi^2$ value  | 119.0 | 254.3 |1452.7   |381.6   |2214.2| 1535.9|148.0|128.5|

### fitting results of PMTs0
<p align="center">
<img src="califigs/wouwoo1103/PMTnperes0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2_0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2zoomin_0PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs1
<p align="center">
<img src="califigs/wouwoo1103/PMTnperes1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2_1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2zoomin_1PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs2
<p align="center">
<img src="califigs/wouwoo1103/PMTnperes2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2_2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2zoomin_2PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs3
<p align="center">
<img src="califigs/wouwoo1103/PMTnperes3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2_3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2zoomin_3PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs4
<p align="center">
<img src="califigs/wouwoo1103/PMTnperes4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2_4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2zoomin_4PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs5
<p align="center">
<img src="califigs/wouwoo1103/PMTnperes5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2_5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2zoomin_5PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs6
<p align="center">
<img src="califigs/wouwoo1103/PMTnperes6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2_6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2zoomin_6PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs7
<p align="center">
<img src="califigs/wouwoo1103/PMTnperes7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2_7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo1103/chi2zoomin_7PMTnpefilelist20.png" width="900" />
</p>
