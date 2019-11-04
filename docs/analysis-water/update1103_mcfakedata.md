## fitting chi2 with MC as fake data.(with all bins)
water attenuation length=20m;bin width=1p.e/bin; the MC' histogram was filled with a factor 0.729 as fake data histogram.
$r=10$ is the ratio of total event number from MC and MC', each event in MC is multiplied by the calibration factor $f$ then filled into the MC histogram. After scaling the MC histogram with $r$, the definition of $\chi^2$
$$
\chi^2 =\sum_{n=0}^{n=max\_bin}(\frac{N'_{n,MC}-N_{n,MC}}{\sigma_{n}})^2
$$
where $f$ is the calibration factor, max\_bin is the bin converted by all the bins in orignal histogram with count less than10;$N'_{n,MC}$ is the count of nth bin in MC' histogram, $N_{n,MC}$ is the nth bin in MC histogram. $\sigma_{n}$ is defined as $\sigma_{n}=\sqrt{N_{MC}/r^2+N'_{MC}}$.

| wo 1stbin&wo last bin | 0  | 1 | 2  | 3  |4|5|6|7|
|-----|----|----|---|---|---|---|---|---|
| calibration factor  | 0.709 | 0.729 |0.725   |0.738   |0.569| 0.689|0.703|0.7272|
|  minimum $\chi^2$ value  | 137.5 | 36.5|414.4  |252.1   |60.9| 18.9|24160|41.0|

### fitting results of PMTs0
<p align="center">
<img src="califigs/mcfake/PMTnperes0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2_0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2zoomin_0PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs1
<p align="center">
<img src="califigs/mcfake/PMTnperes1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2_1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2zoomin_1PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs2
<p align="center">
<img src="califigs/mcfake/PMTnperes2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2_2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2zoomin_2PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs3
<p align="center">
<img src="califigs/mcfake/PMTnperes3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2_3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2zoomin_3PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs4
<p align="center">
<img src="califigs/mcfake/PMTnperes4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2_4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2zoomin_4PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs5
<p align="center">
<img src="califigs/mcfake/PMTnperes5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2_5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2zoomin_5PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs6
<p align="center">
<img src="califigs/mcfake/PMTnperes6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2_6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2zoomin_6PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs7
<p align="center">
<img src="califigs/mcfake/PMTnperes7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2_7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/mcfake/chi2zoomin_7PMTnpefilelist20.png" width="900" />
</p>
