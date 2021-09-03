# MLA: A Tool for Multi-Perspective Conformance Checking of Business Processes
Existing conformance checking techniques focus more on the controlflow
perspective rather than other aspects in a business process. This may induce
misleading conformance diagnostics. In this paper, we introduce MLA tool for
multi-perspective conformance checking. In addition to control-flow perspective,
MLA brings data and privacy perspectives’ impact into conformance analysis to
identify all intra- and inter-layer violations. Moreover, the tool can visualize the
context in which data is processed and identify where data have been processed
for unclear or secondary purposes by an authorised role. The tool has been implemented
in the open source ProM framework. The provided user interface and
graphical outputs make interpreting the conformance result simple.

# Running the application
- 1.Install ProM 6.11 which can be downloaded from https://svn.win.tue.nl/trac/prom/wiki/ProM611
- 2.Run ProM Package Manager by double click on ProMPM611.exe
- 3.Install "LpSolve" and "MultiLayerAlignment" packages from the Not installed tab.
- 4.Run PROM workspace by double click on "ProM611.exe".
- 5.Follow the steps in the MLA manual document to run the MultiLayerAlignment plugin and performing multi-perspective conformance checking.
- The detail information about the inputs/outputs and the tool tutorial are provided in MLA Manual.pdf.
- you can find a sample of each input in the "inputs sample" folder.
- The screen-cast of the tool is available under the name MLA Screencasts.zip.
