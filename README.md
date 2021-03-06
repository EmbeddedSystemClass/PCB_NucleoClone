# PCB_NucleoClone Description
Github SVN repository for UBC Thunderbots PCB_NucleoClone Altium project files. 

# How to link repository with Altium Designer
## Required software
1. git
2. github GUI (optional, I am using GitHub Desktop)
2. Altium Designer

## Instructions
1. Create a working branch of Master in github.
1. Clone your working branch of the UBC-Thunderbots/PCB_NucleoClone repo to your PC (i.e. C:/Documents/GitHub/PCB_NucleoClone)
2. In Altium Designer, navigate to **Preferences** -> **Data Management** -> **Version Control** and ensure *SVN - Subversion* is enabled and Version 1.9 is selected.
4. In Altium Designer, navigate to **Preferences** -> **Data Management** -> **Design Repositories**.
5. Within **Design Repositories** click on on *Connect To* -> *SVN*.
6. In the dialogue box that comes up, fill in the following information:

Field | Selection/Input
--- | ---
Name | PCB_NucleoClone
Default Checkout Path | *location of the cloned UBC-Thunderbots/PCB_MotorDriver repository (i.e. C:/Documents/GitHub/PCB_NucleoClone)*
Method | https
Server | github.com
Server Port | Default
Repository Subfolder | /UBC-Thunderbots/PCB_NucleoClone
User Name | *your github login username*
Password | *your github login password*

7. Click *Test* and pray.
8. Celebrate!

After your repository is connected, you can add or remove files like a regular Altium Project folder and then commit them from within Altium Designer by right-clicking on any project files in the **Projects** and hovering the mouse cursor over **Version Control**. When you have finsihed making your changes to your branch, submit a pull request to have it merged with Master.

Reference page: https://forum.live.altium.com/#posts/235981/718003
