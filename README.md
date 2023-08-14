# Living Off the Foreign Land Cmdlets and Binaries

<img src="https://lofl-project.github.io/assets/logo.png" height="250">

The different files can be easily browsed through a fancy frontend here: https://lofl-project.github.io (All credits for web page front -and backend: [LOLBAS](https://lolbas-project.github.io/) and [GTFOBins](https://gtfobins.github.io/))

The objective of the LOFL project is to document every cmdlet, binary, script, and WMI class that can be used for Living Off the Foreign Land techniques.

The blog which introduces Living Off the Foreign Land can be found at the [BITSADMIN blog](https://blog.bitsadmin.com/living-off-the-foreign-land-windows-as-offensive-platform).

## Criteria

A LOFLCmdlet/Bin/Script/WMIClass must:

* Be an official Microsoft cmdlet or file, either native to the OS or downloaded from Microsoft
* Have the ability to perform actions on a remote system
* Have functionality that would be useful to an APT or red team

Interesting functionality can include:

* Arbitrary code execution
* Query or interact with processes
* Query or interact with user sessions
* Query or modify the registry
* Query or modify the domain
* Manage services
* Perform file operations
* Surveillance (e.g. keylogger, network trace)
* Querying log files or tampering with them

## Contributing

If you have found a new LOFLCmdlet, LOFLBin, LOFLScript or LOFLWMIClass that you would like to contribute, please review the contributing guidelines located here: https://github.com/LOFL-Project/LOFLCAB/blob/master/CONTRIBUTING.md

A template for the required format has been provided here: https://github.com/LOFL-Project/LOFLCAB/blob/master/YML-Template.yml

## Notice

* Please refer to NOTICE.md for license information
