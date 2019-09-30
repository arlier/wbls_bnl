# software and notes in this study
factors which will decide the N p.e distibution of each PMT:
- light source, energy deposition
- propagation (absorption, scattering)
- detection(view the acrylic,optical cookie and PMT as an effective or vitual
detector)

The cosmic muons can be viewed as a stable particle source, with stable flux and
energy for the time scope of experiment. we use CRY as the muon generator.

...............................................................................

Use GEANT4 to simulate the light propagation in water sonsidering the
absorptance of watwer, efficiency of optical cookie, QE of PMT, refraction and
reflection of acrylic vessel etc.

...............................................................................

The simulation framework is ”rat-pac”2 , which is is intended to be a framework
that combines both Monte Carlo simulation of the Braidwood detector with
event-based analysis tasks, like reconstruction.


the MC data is saved in a tree `PMTnpe10m.root` which contains a vector of npe of each PMT and each event.

How to access the dun0001 by ssh tunneling?
in the file `~/.ssh/config` add
``` bash
Host  dune0001
User          zhaor
HostName      dune0001
ProxyCommand  ssh -i ~/mykey -XY zhaor@rssh02.rhic.bnl.gov nc %h %p 2> /dev/null

```


## input parameters of MC simulation
refractive index of water and WbLS:
<p align="center">
<img src="figures/rindex_water.png" width="900" />
</p>

absorption length of water:
<p align="center">
<img src="figures/absorption-length_water.png" width="900" />
</p>

rayleigh scattering length of WbLS:
<p align="center">
<img src="figures/rslength.png" width="900" />
</p>

attenuation length of WbLS:
<p align="center">
<img src="figures/attlength.png" width="900" />
</p>

scintillation spectrum of WbLS:
<p align="center">
<img src="figures/scint.png" width="900" />
</p>

quantum yield of WbLS:
<p align="center">
<img src="figures/qy.png" width="900" />
</p>

