# Urho3D Spherical World
-----------------------------------------------------------------------------------

Description
-----------------------------------------------------------------------------------
Spherical world sample for Urho3D.

Known Issue: Bullet does not process the vertical jump impulse correctly when the unit vector components x and   
y ~= abs(0.707) or when z and y ~= abs(0.707). This note can be seen in Character.cpp, line 148.


Screenshots
-----------------------------------------------------------------------------------
![alt tag](https://github.com/Lumak/Urho3D-Spherical-World/blob/master/screenshot/sphericalworld.jpg)


To Build
-----------------------------------------------------------------------------------
To build it, unzip/drop the repository into your Urho3D/ folder and build it the same way as you'd build the default Samples that come with Urho3D.

License
-----------------------------------------------------------------------------------
The MIT License (MIT)










