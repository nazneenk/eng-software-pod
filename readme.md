#rLoop Pod Firmware
_Lachlan Grogan_

Please make sure you review our [code standards](FIRMWARE/CODE_STANDARD/rloop_code_standard.txt)
and [contributing document.](CONTRIBUTING.md) Also check out our [Confluence page](http://confluence.rloop.org/display/SD/CTRL+Team+Page)

Setup Development Tools:
-----------------------------
1. Get CCS V6.1.2.00015 from the tools folder.
If you are on OS/X check [here](http://processors.wiki.ti.com/index.php/Category:Code_Composer_Studio_v6?keyMatch=CCSV6&tisearch=Search-EN-Everything)
2. When installing make sure you have setup for TI RM4 support


GIT:
-----------------------------
1. Install Git Desktop
2. Clone github.com:rLoopTeamp/eng-software-pod into a folder


CCS - Initial Use
-----------------------------
CCS relies on the notion of a workspace, you need to create a workspace folder and then import the projects into the folder.

1. create a folder at FIRMWARE\WORKSPACE or FIRMWARE\VERIFICATION\WORKSPACE
2. Open CCSV6
3. When prompted, enter the full path to the workspace folder on your local drive.
4. Choose File->Import and select any of the firmware projects under the firmware root or any projects under the verification root.
5. Paths should be good to go.
6. Avoid commiting anything from the WORKSPACE folders and .gitignore is setup to handle this automatically.

Compiler Version
-----------------------------
We are using the TI ARM v15.12.3.LTS (Long Term Support) C Compiler which has already been configured in the project files.

1. Open a CCSV6 workspace
2. Choose Help -> Install new Software
3. From the drop down list box "work with:" Choose --All Available Sites--
4. Expand TI Compiler Updates
5. Select ARM Compiler Tools Version 15.12.3
6. Choose Next/Finish and follow the prompts






