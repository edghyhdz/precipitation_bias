# Precipitation bias
Precipitation bias analysis due to different sampling intervals.


Measurement underestimation is something that could lead to potential damages,  more concern should be considered when these measurements are used for the design of structures that compromise social and economic aspects if flawed. That is the case for `maximum precipitation` measurements and their use for hydraulic structure and flood designs.  The `Hershfield Factor`, HF, a correction factor which increases the underestimated precipitation measurement by a factor of `1.13` is used for this purpose, it was nevertheless derived using a `daily scale`.  In this project, a `one minute` resolution precipitation data set, composed of several Iowa stations, was used to test different outcomes when dealing with a sampling  procedure  that uses  a  fixed  time  interval.   Inasmuch  as  this  data  has  a  really fine  resolution  of  one  minute,  it  was  used  as  the  **`true`** rain  intensity.  It  was  therefore aggregated from the original one minute resolution into different `higher` time durations by also taking into consideration all possible sampling starting points in time.  This way, the sampling behavior was simulated and thus the existing bias associated to it was known. With the use of a peak over threshold analysis, depth duration frequency curves, `DDF`,for the simulated different sampling outcomes were computed.  By means of these DDF curves, a bias was computed and expressed in this project as a correction factor, which as the HF, should be used to correct the likely underestimated maximum precipitation value which was initially measured


>**NOTE:** if you want to see the code rendered via nbviewer click [here](https://nbviewer.jupyter.org/github/edghyhdz/precipitation_bias/blob/master/Precipitation_bias_example.ipynb), otherwise just click on the `Precipitation_bias_example.ipynb` file on this repository. **The table of contents does not work when rendered via GITHUB!**

