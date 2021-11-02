Main Window
===========
The Main Window shows an interactive view of the galactic plane (longitude from -180° to +180° and latitude from -2° to 2°). This view can be used to perform a visual selection of the region of interest.

The selection of the region can be carried out choosing a point on the map and then specifying the radius of selection, or picking up a rectangular region.

It is also possible to specify the surveys and wavelengths for the VLKB query using the checkboxes on the right panel.

.. _main-window:
.. figure:: images/main_window.png
    :alt: Main window

    Main window interface

Clicking on the :guilabel:`Query` button, VLVA sends the query to the VLKB and then opens on a separate window the FITS image containing selected region, in the chosen survey and wavelength, that is used as starting point for performing the visual analytic operations.

VLVA allows to load a FITS file image that is locally stored on the user's computer by clicking on the :guilabel:`Local Image` button.

Similarly, the :guilabel:`Local DC` button allows to load and visualize a velocity datacube FITS file that is already stored on a local disk. When loading a datacube, VLVA will also compute the zeroth moment map which will be visualized as a 2D image layer.
The VLKB search functionality is also extended to imported files.

The :guilabel:`Select` button under the 3D section allows to specify the range of coordinates on which to perform a 3D visualization of compact sources on the galactic plane (:ref:`3d-sources-sect`).
