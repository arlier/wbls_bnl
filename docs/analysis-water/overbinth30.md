
## fitting chi2 without first and without last bin, overbinth=30.
water attenuation length=20m;bin number=50;
$r=10$ is the ratio of total event number from MC and data, after scaling the MC histogram with $r$, the definition of $\chi^2$
$$
\chi^2 =\sum_{n=1}^{n=max\_bin-1}\frac{N_{n,data}-f*N_{n,MC}}{\sigma_{n}}
$$
where $f$ is the calibration factor, max\_bin is the bin converted by all the bins in orignal histogram with count less than10;$N_{n,data}$ is the count of nth bin in data histogram, $N_{n,MC}$ is the nth bin in MC histogram. $\sigma_{n}$ is defined as $\sigma_{n}=\sqrt{N_{MC}/r^2+N_{data}}$.

| wo 1stbin&wo last bin | 0  | 1 | 2  | 3  |4|5|6|7|
|-----|----|----|---|---|---|---|---|---|
| calibration factor  | 0.904 | 0.702 |0.475   |0.858   |1.554| 1.638|1.11|0.84|
|  minimum $\chi^2$ value  | 117.2 | 229. |1328.3   |359.1   |2052.9| 1403.7|133.8|114.6|

### fitting results of PMTs0
<p align="center">
<img src="califigs/overbinth30/PMTnperes0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2_0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2zoomin_0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/PMTnperes0_cf0.902600cf1=0.902800overbinth=30check.png" width="900" />
</p>

### fitting results of PMTs1
<p align="center">
<img src="califigs/overbinth30/PMTnperes1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2_1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2zoomin_1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/PMTnperes1_cf0.697000cf1=0.702200overbinth=30check.png" width="900" />
</p>

### fitting results of PMTs2
<p align="center">
<img src="califigs/overbinth30/PMTnperes2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2_2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2zoomin_2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/PMTnperes2_cf0.475400cf1=0.478000overbinth=30check.png" width="900" />
</p>

### fitting results of PMTs3
<p align="center">
<img src="califigs/overbinth30/PMTnperes3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2_3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2zoomin_3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/PMTnperes3_cf0.856400cf1=0.857600overbinth=30check.png" width="900" />
</p>

### fitting results of PMTs4
<p align="center">
<img src="califigs/overbinth30/PMTnperes4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2_4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2zoomin_4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/PMTnperes4_cf1.554400cf1=1.550000overbinth=30check.png" width="900" />
</p>

### fitting results of PMTs5
<p align="center">
<img src="califigs/overbinth30/PMTnperes5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2_5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2zoomin_5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/PMTnperes5_cf1.635000cf1=1.640000overbinth=30check.png" width="900" />
</p>

### fitting results of PMTs6
<p align="center">
<img src="califigs/overbinth30/PMTnperes6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2_6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2zoomin_6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/PMTnperes6_cf1.116000cf1=1.118000overbinth=30check.png" width="900" />
</p>

### fitting results of PMTs7
<p align="center">
<img src="califigs/overbinth30/PMTnperes7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2_7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/chi2zoomin_7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/overbinth30/PMTnperes7_cf0.838000cf1=0.840000overbinth=30check.png" width="900" />
</p>
