![header](.images/mscode_header.png)

Code Repository for Melis, Siwanowicz, and Dickinson 2023

### Contents

The software is organized into 7 submodules: flynet, flynet-kalman,
flynet-optimizer, latent-analysis, mpc-simulations, robofly and wing-hinge-cnn.
Each submodule is a self contained and can be installed separately. The
installation instructions, system requirements and dependency information is
given separately for each submodule in thier respective sub-folders..

* **flynet** neural network and GUI application for automatically extracting
  wing kinematics from movie sequences. Contains code for generating extended
  data figure 2.

* **flynet-kalman** Python C extension module implementing the Kalman filter
  used by the flynet application.

* **flynet-optimizer** Python C extesion modules implement the particle swarm
  optimization used by the flynet application. 

* **latent-analysis** Python library and Jupyter notebook for performing the
  latent analysis calculations. Contains code for generating  figure 6 and
  extended data figure 8.

* **mpc-simulations** Python library + Jupyter notebook for performing model
  predictive control simulations. Contains code for generating figure 5 and
  extended data figure 7.

* **robofly** Python library + Jupyter notebook for extracting force and torque
  data from the robofly experiments. Also, produces the lollipop figures
  showing forces and torques as arrows on 3D rendering of fly + wing
  kinematics. Contains code for generating figures 5 and 6.

* wing-hinge-cnn Python library + Jupyter notebook for wing hinge cnn. Contains
  code for generating figure 3, figure 4 and extended data figure 3.  

### Cloning the repositry

To clone the repository and create a local copy run the following command.

```bash
git clone --recurse-submodules https://github.com/FlyRanch/mscode-melis-siwanowicz-dickinson
```

### Installation Instructions

The installation instructions for each submodule is given separately in that
submodule. 

### System requirements

All software tested on ubuntu 22.04. 
