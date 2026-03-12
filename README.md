# InverseTHzSim
A differentiable electromagnetic wave simulator at mm-wave and terahertz frequencies for reconstruction-free parameter estimation.

Repository for the paper ["Direct Detection of Object Parameters from Raw Data in MIMO-SAR Imaging at 235-270 GHz via Inverse Simulation"](https://ieeexplore.ieee.org/document/11242135).

## Insturctions
- Compile and build mitsuba3 following the instructions at https://mitsuba.readthedocs.io/en/stable/src/developer_guide/compiling.html
- Make sure to include 'cuda_mono' and 'cuda_ad_mono' to 'mitsuba.conf'
- Setup the python environment using requirements.txt
- Add the datafiles under data/rdm/real/calibrated64
- The Dataset can be found under https://dx.doi.org/10.21227/8jb1-x962
- Prepare a configuration file under data/configurations; see src/config.py

citation:
```
@ARTICLE{saleh2026direct,
  author={Saleh, Mohamed and Kahl, Matthias and Bolívar, Peter Haring and Kolb, Andreas},
  journal={IEEE Journal of Microwaves}, 
  title={Direct Detection of Object Parameters From Raw Data in MIMO-SAR Imaging at 235–270 GHz via Inverse Simulation}, 
  year={2026},
  volume={6},
  number={1},
  pages={126-136},
  keywords={Image reconstruction;Imaging;Receivers;Radar imaging;Synthetic aperture radar;Rendering (computer graphics);Accuracy;MIMO;Transmitters;Three-dimensional displays;Backpropagation;computer simulation;MIMO radar;ray tracing;terahertz radiation},
  doi={10.1109/JMW.2025.3627070}}
```
