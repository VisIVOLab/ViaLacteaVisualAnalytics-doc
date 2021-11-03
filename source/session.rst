Session management
==================
VLVA allows to save the work session and restore it later.
The session is a folder containing a JSON configuration file and all the files required to resume the visual analysis operations.

Saving a session locally
------------------------
The session includes:

* the image layers and their settings (color palette, scale, transparency level, whether or not they are visualized);
* compact sources (color, whether or not they are visualized);
* filaments (color, whether or not they are visualized);
* datacube windows and their settings (threshold, cutting plane and contours values).

To save the session, from the 2D visualization window go to menu :menuselection:`File --> Save session` and then select an empty folder on the local disk. If you try to save a previously loaded or already saved session, the tool will ask whether to overwrite the current session or save it in a separate folder.

Loading a session locally
-------------------------
To load a session, from the Main Window go to menu :menuselection:`File --> Load session` and then select the :file:`session.json` file inside a session folder. VLVA will restore the status of the work session as it was saved. 
