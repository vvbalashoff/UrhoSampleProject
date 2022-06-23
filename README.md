# Urho Sample Project

Relatively simple Urho example project.

It's updated to Urho 1.7.1 version:
  - fixed folder name to run on case sensitive file systems;
  - CoreData is taken from actual Urho3d version to fix missing particle effects due to wrong shaders.

# How to compile in Linux

For example:
project folder: /home/vvb/src/urho3d/UrhoSampleProject
Urho3d folder: /home/vvb/src/build/urho3d/urho3d (where your _compiled_ Urho3d is located)
build folder: /home/vvb/src/build/urho3d/UrhoSampleProject

cd to build folder and run following commands:

export URHO3D_HOME=/home/vvb/src/build/urho3d/urho3d
cmake ../UrhoSampleProject
make
