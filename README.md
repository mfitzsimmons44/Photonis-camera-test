Jupiter Notebook and example data for "Prospects for a camera-based detector for Neutron Reflectometry"

This site contains:

(1) A report on testing of the Photonis Timepix3 camera for a Neutron Reflectometry application.  

(2) Two examples of measurements in the RawData sub-directory called A35.tpx3 (neutron shutter closed) and xframes_000009.tpx3 (neutron shutter open).

(3) A Jupiter Notebook that will convert tpx3 files into hdf5 files (in the HDF5Folder) and fix timing errors (these involve rollover of the timing chip). The conversion from tpx3 to hdf5 formats requires a copyrighted routine called tpx3-analyze (https://www.amscins.com/), so the executable is not included in this website. Binary data consisting of the 2-dimensional position and absolute time of each event are written to a NumPy binary file (in the BinaryFolder). Plots of the intensity integrated over all position vs. time, and intensity integrated over all time vs. position are written to PlotFolder.

M.R. Fitzsimmons

20.10.22

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7231893.svg)](https://doi.org/10.5281/zenodo.7231893)


