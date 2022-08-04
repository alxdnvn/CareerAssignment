# VM Builder

## Description

VM builder (VMB) is a tool for packaging virtual machine installations into a single executable for multiple deployments.  VMB is targeted at students that want to be able to rapidly reinstall a VM, or create a second copy of an existing VM without variation between installs.  To prepare an installation for VMB conversion, users download their desired operating system .ISO and the desired version of Oracle VirtualBox, then define installation options for repeatable deployment in the presets.txt file.

## Installation

##### Requirements to package an install
- VMB.exe
- A completed presets.txt file
- Oracle VirtualBox Installer (VirtualBox-X.X.XX-XXXXX-Win.exe)
- Your operating system .ISO (operatingsystem.iso)

##### Execution
- Run VMB.exe and select your Oracle VirtualBox installer and OS .ISO in the appropriate dropdowns.
- Select "Install"


## Contributing

I recommend the following guide for beginners that want to help with VM Builder:

[First Contributions](https://github.com/firstcontributions/first-contributions)

## New to Virtual Machines? (AKA I have no idea why this repo was recommended to me)

Before using this tool, it is recommended to become familiar with the options users choose when installing a VM, the below guide covers installing Ubuntu in Windows 10 and can be used a baseline for building your first VM Builder presets.txt file.

[Learning to Use Virtual Machines](https://github.com/alxdnvn/CareerAssignment/blob/main/Learning%20to%20Use%20Virtual%20Machines.pdf)


