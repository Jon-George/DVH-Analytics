# DVH-Analytics

<h3 align="center">
  <img src="https://user-images.githubusercontent.com/4778878/30754005-b7a7e808-9f86-11e7-8b0f-79d1006babdf.jpg" alt="fastlane Logo" />
</h3>

# DVH Analytics

Welcome to the brand new DVH Analytics, rewritten as a native OS application with wxPython. This version is currently 
only available as source code during the public beta. Compiled versions will be available after successful testing.

DVH Analytics is a software application to help radiation oncology departments build an in-house database of treatment 
planning data for the purpose of historical comparisons and statistical analysis.

The application builds a SQL database of DVHs and various planning parameters from DICOM files 
(i.e., Plan, Structure, Dose). Since the data is extracted directly from DICOM files, we intend
to accommodate an array of treatment planning system vendors.

<img src='https://user-images.githubusercontent.com/4778878/60750740-c9120400-9f72-11e9-8c70-a735eb03c6e0.jpg' align='right' width='400' alt="DVH Analytics screenshot">
<img src='https://user-images.githubusercontent.com/4778878/60750758-ff4f8380-9f72-11e9-881d-eef7fa1efc95.jpg' align='right' width='400' alt="DVH Analytics screenshot">


In addition to viewing DVH data, this software provides methods to:

- download queried data
- create time-series plots of various planning and dosimetric variables
- calculate correlations
- generate multi-variable linear and machine learning regressions.


The code is built upon these core libraries:
* [wxPython Phoenix](https://github.com/wxWidgets/Phoenix) - Build a native GUI on Windows, Mac, or Unix systems
* [Pydicom](http://code.google.com/p/pydicom/) - Read, modify and write DICOM files with python code
* [dicompyler-core](https://pypi.python.org/pypi/dicompyler-core) - Extensible radiation therapy research platform and viewer for DICOM and DICOM RT
* [Bokeh](http://bokeh.pydata.org/en/latest/index.html) - Interactive Web Plotting for Python

For installation instructions of the source code, see our [installation notes](https://github.com/cutright/DVH-Analytics/blob/master/install_notes.md).


### Citing DVH Analytics
DOI: [https://doi.org/10.1002/acm2.12401](https://doi.org/10.1002/acm2.12401)  
“DVH Analytics: A DVH Database for Clinicians and Researchers,” J. App. Clin. Med. Phys. - JACMP-2018-01083


## Dependencies
* [Python](https://www.python.org) >=3.5
* [wxPython Phoenix](https://github.com/wxWidgets/Phoenix) >= 4.0.4
* [Pydicom](https://github.com/darcymason/pydicom) >=1.0
* [dicompyler-core](https://pypi.python.org/pypi/dicompyler-core) 0.5.3
* [Bokeh](http://bokeh.pydata.org/en/latest/index.html) >= 1.2.0
* [PostgreSQL](https://www.postgresql.org/) and [psycopg2](http://initd.org/psycopg/)
* [SciPy](https://scipy.org)
* [NumPy](http://numpy.org)
* [Shapely](https://github.com/Toblerity/Shapely)
* [Statsmodels](https://github.com/statsmodels/statsmodels) 0.8.0
* [Scikit-learn](http://scikit-learn.org)
* [regressors](https://pypi.org/project/regressors/)

