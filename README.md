# mkmr_sw

Solidworks-urdf files of the Melih Korkmaz Mobile Robot 


# SolidWorks to URDF Exporter


The SolidWorks to URDF exporter is a SolidWorks add-in that allows for the convenient export of SW Parts and Assemblies into a URDF file. The exporter will create a ROS-like package that contains a directory for meshes, textures and robots (urdf files). For single SolidWorks parts, the part exporter will pull the material properties and create a single link in the URDF. For assemblies, the exporter will build the links and create a tree based on the SW assembly hierarchy. The exporter can automatically determine the proper joint type, joint transforms, and axes.


See the [ROS Wiki](https://github.com/ros/solidworks_urdf_exporter), [GitHub](https://github.com/ros/solidworks_urdf_exporter) and associated [tutorials](http://wiki.ros.org/sw_urdf_exporter/Tutorials).

For download [click](https://github.com/mkorkmz/mkmr_sw/raw/main/sw2urdfSetup.exe)

### Note !! After extracting the urdf file from Solidworks, some updates are required to use it in your ROS project , especially if it is in a simulation environment.

  ## Image

<table>
  <tr>
    <td><img src="https://github.com/mkmr-software/mkmr_sw/blob/main/mkmr_sw_img/preview1.JPG?raw=true" width="500"></td>
    <td><img src="https://github.com/mkmr-software/mkmr_sw/blob/main/mkmr_sw_img/preview2.JPG?raw=true" width="500"></td>
  </tr>
  
  <tr>
    <td colspan="2">&nbsp;<img src="https://github.com/mkmr-software/mkmr_sw/blob/main/mkmr_sw_img/ss3.png?raw=true" width="1000"></td>
  </tr>
  
</table>


<img src="https://github.com/mkmr-software/mkmr_sw/blob/main/mkmr_sw_img/sw_exporter_initial.png?raw=true">
<img src="https://github.com/mkmr-software/mkmr_sw/blob/main/mkmr_sw_img/sw_exporter_config.png?raw=true">
<img src="https://github.com/mkmr-software/mkmr_sw/blob/main/mkmr_sw_img/sw_exporter_joints.png?raw=true">
<img src="https://github.com/mkmr-software/mkmr_sw/blob/main/mkmr_sw_img/sw_exporter_links.png?raw=true">
