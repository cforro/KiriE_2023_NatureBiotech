This is the workflow to create a mesh electrode array, convert it to triangulated meshes, and compute the mesh strain.
This repository is being updated periodically. For questions, write to cforro@stanford.edu

Contents:
  - Notebook to create .gds layout : 'Create_device.ipynb'. Relies on PHIDL
  - Two .gds files, the device and its negative complementary file (see Create_device.ipynb). Necessary to create a triangulation
  - Notebook to create triangulation 'Create_mesh.ipynb'
  - Python File : Naghdi_mesh*.py to compute the strains under self weight and the weight of an organoid.
  - Two mesh files *.h5 and *.xdmf necessary, and loaded by the python file
