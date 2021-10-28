Installation
============
VLVA is an open-source software available for macOS and Linux systems. The source code is available on `GitHub <https://github.com/NEANIAS-Space/ViaLacteaVisualAnalytics>`_.

To manually build and install VLVA (with its dependencies), follow the steps provided `here <https://github.com/NEANIAS-Space/ViaLacteaVisualAnalytics/blob/master/INSTALL.md>`_.

Pre-compiled DMG and Debian packages are available on the `GitHub Releases page <https://github.com/NEANIAS-Space/ViaLacteaVisualAnalytics/releases>`_.

Docker container
----------------
VLVA is also available as a Docker container. The container leverages Virtual Network Computing (VNC) and can be easily accessed through a browser.

To start a new container, use the following command:

::

    $ docker run -it -e SIZEW=1920 -e SIZEH=1080 -e CDEPTH=24 -e SHARED=TRUE -e VNCPASS=vncpasswd -p 5901:5901 neaniasspace/vialacteavisualanalytics:latest

Then open a browser and go to http://localhost:5901/. The default password is "vncpasswd" (see the :envvar:`VNCPASS` value defined in the Docker command).

Before starting VLVA change the scaling mode (:menuselection:`Settings --> Scaling Mode --> Remote Resizing`) and enable fullscreen (see :numref:`vnc-window`).

.. _vnc-window:
.. figure:: images/vnc.png
    :align: center
    :alt: VNC settings

    VNC settings

Now you can start VLVA using the icon on the desktop.

.. _vialactea-docker:
.. figure:: images/vialactea_docker.png
    :alt: ViaLactea Docker container

    ViaLactea Docker container
