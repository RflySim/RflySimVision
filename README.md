# RflySimVision
[![An example for RflySimVision](https://res.cloudinary.com/marcomontalbano/image/upload/v1679997079/video_to_markdown/images/youtube--Abd9i0Ni7SQ-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=ZIis42qveZA)
# #Installation
Requirements: Windows10/11
1. Download and configure the RFlysim platform according to the tutorial of https://rflysim.com/docs/#/en/2_Configuration/SoftwareInstallation
2. Download the demo code of RflySimVision at [https://github.com/Ding-Guo/RflySimVision.git](https://github.com/Ding-Guo/RflySimVision.git)
3. open wsl  
```
mv RflySimVision/ego-planner-swarm RflySimVision/sensor_pkg /home 
cd /home/ego-planner-swarm
catkin_make
``` 
## Autonomous exploration
### Windows
```
cd RflySimVision
SingleRun.bat
```
### WSL
```
cd /home/ego-planner-swarm/shfiles
bash single.sh
```
<p align = "center">
<img src="pictures/demo1.gif" width = "576" height = "324" border="5" />
</p>

## Swarm exploration
### Windows
```
cd RflySimVision
SwarmRun.bat
```
### WSL
```
cd /home/ego-planner-swarm/shfiles
bash swarm.sh
```
<p align = "center">
<img src="pictures/demo2.gif" width = "576" height = "324" border="5" />
</p>