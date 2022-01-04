```
Dial Plan Visualizer - see a graph of the call flow for
any Inbound Route.
```
### What?
Updated fork of  abqcheeks / cpviz 
This is a module for [FreePBX©](http://www.freepbx.org/ "FreePBX Home Page"), an open source graphical user interface to control and manage [Asterisk(http://www.asterisk.org/ "Asterisk Home Page") phone systems.  FreePBX is licensed under GPL.
The cpviz module shows you a graph of the call flow for any Inbound Route.  End-user PBX support often involves making changes to the flow for inbound calls, or simply asking questions about it (e.g. "Whose phones ring when someone calls X?  When we get a call on Y does it go directly to the IVR or are there Time Conditions applied first?").

### Installing the module
* Download cpviz.tar.gz or cpviz.zip to your computer.
* Log in to your FreePBX system, go to Admin > Module Admin
* Click Upload Modules
* Set the type to "Upload (From Hard Disk)"
* Select "Choose File" to select cpviz.tar.gz or cpviz.zip, then click "Upload (From Hard Disk)"
* Click the "local module administration" link
* Scroll down to Dial Plan Visualizer in the Reports section, click it, then click the Install action.
* Click the Process button at the bottom of the page.

### Using the module
* Log in to your PBX, go to Reports > Dial Plan Visualizer
* Select an inbound route from the drop-down menu
* Click "Visualize Dial Plan"
The graph for that route should be displayed.  The graph is
not interractive, it is simply meant to provide a view
of the call plan.

### License
[This modules code is licensed as GPLv3+](http://www.gnu.org/licenses/gpl-3.0.txt)

### Issues
Please file bug reports via the github Issues tracker