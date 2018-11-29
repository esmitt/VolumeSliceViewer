Volume Slicer Viewer
===================

This simple code is performed in Jupyter to show the different anatomical planes of a DICOMDIR volume.
It is necessary to install `ipykernel`, `pydicom` and `ipywidgets` (using pip or conda)

Now, sometimes it is necessary to enable the notebook extension for widgets (jupyter in my case, ):
```sh
jupyter nbextension enable --py widgetsnbextension
```
The code shows the path of my local machine for the DICOMDIR (in the variable filepath) at beginning of the script. Also, it considers the 1st serie, and the 1st study (just for testing purposes).

###### If you want to contribute to this project and make it better, your help is very welcome.
