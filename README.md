# raw-panel-dummies-releases
Releases for the Raw Panel Dummies emulator tool

Raw Panel Dummies allows you to emulate SKAARHOJ hardware panels in a webbrowser and communicate with them over the rawpanel protocol

You find releases under the releases section on this repository

[CLICK HERE for Release downloads](https://github.com/SKAARHOJ/raw-panel-dummies-releases/releases)

Here are some links to instructions for using Raw Panel Dummies on [Mac](https://wiki.skaarhoj.com/books/applications/page/running-cli-applications-mac) and [Windows](https://wiki.skaarhoj.com/books/applications/page/running-cli-applications-windows)

To play with Raw Panel Dummies we strongly advice you to download another tool - a client - that can connect to the panels and help you explore how Raw Panel protocol works. Go to [Raw Panel Explorer](https://github.com/SKAARHOJ/raw-panel-explorer/releases)

## Legacy and External Panel Topologies
The file raw-panel-dummies-profile_LegaciesAndExternalPanels.zip contains folders with topologies for a number of legacy UniSketch panels as well as some external panels like StreamDecks. This can be used to simulate these panels as they are not embedded in the raw-panel-dummies application. 
Unzip the file and a folder named raw-panel-dummies-profile/ will be created with the profiles inside. Make sure this folder is located in the same directory where the raw-panel-dummies application  is located and run from. You simulate these panels by reference to their sub-folder name using the -panel flag.
