# data analysis of water phase
the valid data: from 20180101 to 20180612, that is run `19885` to `28655`

## strategy of calibration
<p align="center">
<img src="figures/waterom.png"
     width="500" />
</p>
For the through-going muons, GEANT4
simulation can simulate the generation,
propagation of photons in the water, and
the boundaries of acrylic vessel
and PMT. While some of the input parameters (water attenuation length, effeciency of PMTs and optical cookies)are
not perfectly measured.
the attenuation length of water is $20^{+20}_{-10}$m; the QE of PMTs is the
recommended value from vendor and transparency of optical cookies are not well measured; these uncertainties lead us to ’calibrate’ the detector response.


The straightfoward observabl of detector is the np.e. of 8PMTs. 
our strategy is to assume the the discrepancy of CM and data caused by these input parameters can be descibed by a linear `effective factor`. 


.......................................
## dataset-> Hodo-scope data


## dataset-> Multiplicity data

> check the factors using multiplicity-trig data

Once we get the calibration factors $Q_{i}$ , we can perform simulation for the
multiplicity events with these factors fixed. If the simulation of multiplicity events
have consistent results with data, these calibration factors are believed to be
reliable.
