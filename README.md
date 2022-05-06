# robotiq2F_tcp
Python package to control Robotiq2F grippers by wrapping the TCP API defined by the robotiq URCap for Universal Robots.. For an example on how to use, see the `example.py` script.

This wrapper assumes the [URCap](https://assets.robotiq.com/website-assets/support_documents/document/UCG-1.8.9_20220106.zip) for the gripper was installed on the UR3's Control Box.  The wrapper was tested on version UCG-1.8.9.14887 of the Robotiq URcap.


## Getting started
To use this controller, install the python package using `pip install -e <path-to-package-root-folder>`.
Before running the code, ensure your pc is connected to the UR3 robot via an ethernet cable and a corresponding local wired network. To setup the latter, follow these steps (Ubuntu):
* Go to Settings > Network 
* Add a new Wired network by clicking the '+' button
* Add an appropriate name in the Identity tab
* In the IPv4 tab, tick "Shared to other computers"
* Click the green "Add" button, top right
