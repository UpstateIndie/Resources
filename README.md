# Extended GuiObjectView v1.0
An extension to the GuiObjectView class by Jesse Allen.

# Extended Features
* Sub-mesh visibility states
* Sub-mesh skinning support
* Extended camera

# Installation
<h3>Source Code:</h3>
<b>1 -</b> Backup your existing <b>"source\T3D\guiObjectView.h"</b> and <b>"source\T3D\guiObjectView.cpp"</b> files.<br>
<b>2 -</b> Replace <b>"source\T3D\guiObjectView.h"</b> and <b>"source\T3D\guiObjectView.cpp"</b> with the updated files provided.<br>
<b>3 -</b> Recompile. A successful update of the GuiObjectView class will allow the script functions to be used.<br>
<br>
<h3>Script:</h3>
An example script file has been provided, which can be initialized with the other .gui scripts in <b>"scripts\client\init.cs"</b>(as of T3D 3.9, when 4.0 hits expect filepaths for scripts to change). The example script will cause any GuiObjectView control named <b>'PreviewGui'</b> to automatically reset its camera's position when the control's <b>onWake()</b> is called. It is recommended that this script be included to promote a better understanding of the resource and how it is used from script.<br>

# License
All resources are MIT Licensed under the original license included with Torque3D.<br> 
No clauses, no additions, no requirements. Enjoy the resources.<br>
