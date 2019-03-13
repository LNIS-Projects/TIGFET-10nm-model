# TIGFET-10nm-model

This repository contains TIGFET 10nm Model. 

Device can be added in netlist as follow
```
Xxx d pgd cg pgs s TIGFET10nm nw=<val> 
```

Also some sample hspice netlists are added in netlists folder.

## Device Details 
* 7nm thick HfO<sub>2</sub> used as the dielectric 
* Body doping set to 1x10<sup>16</sup> cm-3
* Strained <111> silicon, effectively making the holes 81% faster and the electrons 58% faster
* Si and NiSi work functions were chosen for optimized for symmetric switching 
* Thermal transport (not tunneling) is the dominant method of current transport

