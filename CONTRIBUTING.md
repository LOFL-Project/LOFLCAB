# Contributing

First, thank you for contributing!

When submitting new LOFLCABs, please submit a `yml` sourcefile (`yml/`) as these are used to generate everything else. Next, review `README.md` and ensure that your LOFLCAB meets the criteria--interesting or unexpected functionality that would be useful to an attacker.

There's nothing special about the format. Just base your entry off an existing one and modify as required. Please ensure that you do not add or remove any of the fields; all are required.   

There is a template that can be used located here if you do not want to copy one of the existing LOLs: https://github.com/LOFL-Project/LOFLCAB/blob/master/YML-Template.yml   

## Functions and Toolsets
It is important to use the predefined Functions and Toolsets to make sure the LOFL Project website works as expected. These are defined in the `functions.yml` and `toolsets.yml` files in the `_data` folder of https://github.com/LOFL-Project/LOFL-Project.github.io. For ease, also listed below.

**Available functions**
| Function  | Description                                                   |
+-----------+---------------------------------------------------------------+
| Sessions  | The LOFLCAB can list and interact with sessions               |
| Registry  | The LOFLCAB can query and write the registry                  |
| Manage    | The LOFLCAB can manage services on a server                   |
| Execute   | The LOFLCAB can achieve abitrary code execution               |
| Processes | The LOFLCAB can query and interact with processes             |
| Logs      | The LOFLCAB can query logging                                 |
| Data      | The LOFLCAB can query or access data                          |
| Domain    | The LOFLCAB can query or modify the domain                    |
| Network   | The LOFLCAB can query or configure a network                  |
| Recon     | The LOFLCAB can query information for reconnaissance purposes |
| Misc      | LOFLCAB that does not fit in the other categories             |

**Available toolsets**
| Toolset      | Description                                                                                                                                         |
+--------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| Builtin      | Natively built into Windows 10                                                                                                                      |
| GUI          | Tool which has a graphical user interface                                                                                                           |
| CIMSession   | Tool which uses a CIM session to interact with the remote computer. The New-CimSession cmdlet can be used to initiate the CIM session               |
| PSSession    | Tool which uses a PowerShell Remoting session to interact with the remote computer. The New-PSSession cmdlet can be used to initiate the PS session |
| RSAT         | Tool which is part of the Remote Server Administration Tools (RSAT) which can be installed separately on Windows                                    |
| Server       | Tool which is only available on a Windows Server OS                                                                                                 |
| Sysinternals | Tool which is part of the Sysinternals suite                                                                                                        |
| Extra        | Tool which needs to be installed separately                                                                                                         |


Looking forward for your contributions!
