| 1stbin,u& last bin,o | 0  | 1 | 2  | 3  |4|5|6|7|
|-----|----|----|---|---|---|---|---|---|
| calibration factor wou,woo | 0.907 | 0.695 |0.488   |0.872   |0.992| 1.023|1.109|0.864|
| calibration factor wou,wo | 0.909 | 0.692 |0.488   |0.872   |0.992| 1.023|1.109|0.865|
| calibration factor wu,woo | 0.907 | 0.695 |0.461   |0.857   |1.067| 1.023|1.109|0.840|
| calibration factor wu,wo | 0.909 | 0.689 |.461   |.857   |1.067| 1.023|1.109|0.840|
|  minimum $\chi^2$ value  wou,woo| 181.9 | 291.1 |793.5   |346.2   |135.1| 246.7|176.5|194.6|
|  minimum $\chi^2$ value wou,wo | 189.5 | 293.7 |796.6   |348.6   |136.1| 247|183.8|204.9|
|  minimum $\chi^2$ value  wu,woo| 207.9 | 349.3 |2283.4   |346.2   |2904.7| 2465.6|182.0|261.4|
|  minimum $\chi^2$ value  wu,wo| 215.5 | 350.8 |2286.7   |485.1   |2905.7| 2466.3|189.3|269.2|

<p align="center">
<img src="califigs/npes4s5.png" width="900" />
</p>

*******************************

## fitting chi2 without first and without last bin.
water attenuation length=20m;bin number=50;
$r=10$ is the ratio of total event number from MC and data, after scaling the MC histogram with $r$, the definition of $\chi^2$
$$
\chi^2 =\sum_{n=1}^{n=max\_bin-1}\frac{N_{n,data}-f*N_{n,MC}}{\sigma_{n}}
$$
where $f$ is the calibration factor, max\_bin is the bin converted by all the bins in orignal histogram with count less than10;$N_{n,data}$ is the count of nth bin in data histogram, $N_{n,MC}$ is the nth bin in MC histogram. $\sigma_{n}$ is defined as $\sigma_{n}=\sqrt{N_{MC}/r^2+N_{data}}$.

| wo 1stbin&wo last bin | 0  | 1 | 2  | 3  |4|5|6|7|
|-----|----|----|---|---|---|---|---|---|
| calibration factor  | 0.907 | 0.695 |0.488   |0.872   |0.992| 1.023|1.109|0.864|
|  minimum $\chi^2$ value  | 181.9 | 291.1 |793.5   |346.2   |135.1| 246.7|176.5|194.6|

### fitting results of PMTs0
<p align="center">
<img src="califigs/wouwoo/PMTnperes0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2_0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2zoomin_0PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs1
<p align="center">
<img src="califigs/wouwoo/PMTnperes1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2_1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2zoomin_1PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs2
<p align="center">
<img src="califigs/wouwoo/PMTnperes2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2_2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2zoomin_2PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs3
<p align="center">
<img src="califigs/wouwoo/PMTnperes3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2_3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2zoomin_3PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs4
<p align="center">
<img src="califigs/wouwoo/PMTnperes4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2_4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2zoomin_4PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs5
<p align="center">
<img src="califigs/wouwoo/PMTnperes5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2_5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2zoomin_5PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs6
<p align="center">
<img src="califigs/wouwoo/PMTnperes6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2_6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2zoomin_6PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs7
<p align="center">
<img src="califigs/wouwoo/PMTnperes7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2_7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwoo/chi2zoomin_7PMTnpefilelist20.png" width="900" />
</p>

## fitting chi2 without first and with last bin.
$r=10$ is the ratio of total event number from MC and data, after scaling the MC histogram with $r$, the definition of $\chi^2$
$$
\chi^2 =\sum_{n=1}^{n=max\_bin}\frac{N_{n,data}-f*N_{n,MC}}{\sigma_{n}}
$$
where $f$ is the calibration factor, max\_bin is the bin converted by all the bins in orignal histogram with count less than10;$N_{n,data}$ is the count of nth bin in data histogram, $N_{n,MC}$ is the nth bin in MC histogram. $\sigma_{n}$ is defined as $\sigma_{n}=\sqrt{N_{MC}/r^2+N_{data}}$.

| wo 1stbin&w last bin | 0  | 1 | 2  | 3  |4|5|6|7|
|-----|----|----|---|---|---|---|---|---|
| calibration factor  | 0.909 | 0.692 |0.488   |0.872   |0.992| 1.023|1.109|0.865|
|  minimum $\chi^2$ value  | 189.5 | 293.7 |796.6   |348.6   |136.1| 247|183.8|204.9|

### fitting results of PMTs0
<p align="center">
<img src="califigs/wouwo/PMTnperes0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2_0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2zoomin_0PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs1
<p align="center">
<img src="califigs/wouwo/PMTnperes1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2_1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2zoomin_1PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs2
<p align="center">
<img src="califigs/wouwo/PMTnperes2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2_2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2zoomin_2PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs3
<p align="center">
<img src="califigs/wouwo/PMTnperes3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2_3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2zoomin_3PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs4
<p align="center">
<img src="califigs/wouwo/PMTnperes4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2_4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2zoomin_4PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs5
<p align="center">
<img src="califigs/wouwo/PMTnperes5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2_5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2zoomin_5PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs6
<p align="center">
<img src="califigs/wouwo/PMTnperes6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2_6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2zoomin_6PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs7
<p align="center">
<img src="califigs/wouwo/PMTnperes7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2_7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wouwo/chi2zoomin_7PMTnpefilelist20.png" width="900" />
</p>

## fitting chi2 with first and without last bin.
$r=10$ is the ratio of total event number from MC and data, after scaling the MC histogram with $r$, the definition of $\chi^2$
$$
\chi^2 =\sum_{n=0}^{n=max\_bin-1}\frac{N_{n,data}-f*N_{n,MC}}{\sigma_{n}}
$$
where $f$ is the calibration factor, max\_bin is the bin converted by all the bins in orignal histogram with count less than10;$N_{n,data}$ is the count of nth bin in data histogram, $N_{n,MC}$ is the nth bin in MC histogram. $\sigma_{n}$ is defined as $\sigma_{n}=\sqrt{N_{MC}/r^2+N_{data}}$.

| wo 1stbin&wo last bin | 0  | 1 | 2  | 3  |4|5|6|7|
|-----|----|----|---|---|---|---|---|---|
| calibration factor  | 0.907 | 0.695 |0.461   |0.857   |1.067| 1.023|1.109|0.840|
|  minimum $\chi^2$ value  | 207.9 | 349.3 |2283.4   |346.2   |2904.7| 2465.6|182.0|261.4|

### fitting results of PMTs0
<p align="center">
<img src="califigs/wuwoo/PMTnperes0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2_0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2zoomin_0PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs1
<p align="center">
<img src="califigs/wuwoo/PMTnperes1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2_1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2zoomin_1PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs2
<p align="center">
<img src="califigs/wuwoo/PMTnperes2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2_2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2zoomin_2PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs3
<p align="center">
<img src="califigs/wuwoo/PMTnperes3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2_3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2zoomin_3PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs4
<p align="center">
<img src="califigs/wuwoo/PMTnperes4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2_4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2zoomin_4PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs5
<p align="center">
<img src="califigs/wuwoo/PMTnperes5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2_5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2zoomin_5PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs6
<p align="center">
<img src="califigs/wuwoo/PMTnperes6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2_6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2zoomin_6PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs7
<p align="center">
<img src="califigs/wuwoo/PMTnperes7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2_7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwoo/chi2zoomin_7PMTnpefilelist20.png" width="900" />
</p>

## fitting chi2 with first and with last bin.
$r=10$ is the ratio of total event number from MC and data, after scaling the MC histogram with $r$, the definition of $\chi^2$
$$
\chi^2 =\sum_{n=0}^{n=max\_bin}\frac{N_{n,data}-f*N_{n,MC}}{\sigma_{n}}
$$
where $f$ is the calibration factor, max\_bin is the bin converted by all the bins in orignal histogram with count less than10;$N_{n,data}$ is the count of nth bin in data histogram, $N_{n,MC}$ is the nth bin in MC histogram. $\sigma_{n}$ is defined as $\sigma_{n}=\sqrt{N_{MC}/r^2+N_{data}}$.

| wo 1stbin&wo last bin | 0  | 1 | 2  | 3  |4|5|6|7|
|-----|----|----|---|---|---|---|---|---|
| calibration factor  | 0.909 | 0.689 |.461   |.857   |1.067| 1.023|1.109|0.840|
|  minimum $\chi^2$ value  | 215.5 | 350.8 |2286.7   |485.1   |2905.7| 2466.3|189.3|269.2|

### fitting results of PMTs0
<p align="center">
<img src="califigs/wuwo/PMTnperes0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2_0PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2zoomin_0PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs1
<p align="center">
<img src="califigs/wuwo/PMTnperes1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2_1PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2zoomin_1PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs2
<p align="center">
<img src="califigs/wuwo/PMTnperes2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2_2PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2zoomin_2PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs3
<p align="center">
<img src="califigs/wuwo/PMTnperes3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2_3PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2zoomin_3PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs4
<p align="center">
<img src="califigs/wuwo/PMTnperes4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2_4PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2zoomin_4PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs5
<p align="center">
<img src="califigs/wuwo/PMTnperes5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2_5PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2zoomin_5PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs6
<p align="center">
<img src="califigs/wuwo/PMTnperes6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2_6PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2zoomin_6PMTnpefilelist20.png" width="900" />
</p>

### fitting results of PMTs7
<p align="center">
<img src="califigs/wuwo/PMTnperes7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2_7PMTnpefilelist20.png" width="900" />
</p>
<p align="center">
<img src="califigs/wuwo/chi2zoomin_7PMTnpefilelist20.png" width="900" />
</p>
