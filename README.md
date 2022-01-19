- 👋 Hi, I’m @fossiltx
- 👀 I’m interested in ...QGIS problems
- 🌱 I’m currently learning ...QGIS
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ... Shoptexas@protonmail.com

<!---

I have received the following message when trying to load the cartolinegen file:  I received the followiing error:

Couldn't load plugin 'cartolinegen' due to an error when calling its classFactory() method 
ModuleNotFoundError: No module named 'ogr' 
Traceback (most recent call last):
  File "/Applications/QGIS-LTR.app/Contents/MacOS/../Resources/python/qgis/utils.py", line 334, in _startPlugin
    plugins[packageName] = package.classFactory(iface)
  File "/Users/staylor1/Library/Application Support/QGIS/QGIS3/profiles/default/python/plugins/cartolinegen/__init__.py", line 35, in classFactory
    from .cartolinegen import CartoLineGen
  File "/Applications/QGIS-LTR.app/Contents/MacOS/../Resources/python/qgis/utils.py", line 793, in _import
    mod = _builtin_import(name, globals, locals, fromlist, level)
  File "/Users/staylor1/Library/Application Support/QGIS/QGIS3/profiles/default/python/plugins/cartolinegen/cartolinegen.py", line 36, in 
    from .generalize import Generalize
  File "/Applications/QGIS-LTR.app/Contents/MacOS/../Resources/python/qgis/utils.py", line 793, in _import
    mod = _builtin_import(name, globals, locals, fromlist, level)
  File "/Users/staylor1/Library/Application Support/QGIS/QGIS3/profiles/default/python/plugins/cartolinegen/generalize.py", line 24, in 
    import ogr,sys,math,random,os
  File "/Applications/QGIS-LTR.app/Contents/MacOS/../Resources/python/qgis/utils.py", line 793, in _import
    mod = _builtin_import(name, globals, locals, fromlist, level)
ModuleNotFoundError: No module named 'ogr'

Python version: 3.8.7 (default, Feb 10 2021, 09:04:08) [Clang 12.0.0 (clang-1200.0.32.29)] 
QGIS version: 3.16.16-Hannover Hannover, f5778a89df 
Python Path:
•	/Users/staylor1/Library/Application Support/QGIS/QGIS3/profiles/default/python/plugins/LAStools
•	/Users/staylor1/Library/Application Support/QGIS/QGIS3/profiles/default/python/plugins/contour
•	/Users/staylor1/Library/Application Support/QGIS/QGIS3/profiles/default/python/plugins/network_gt
•	/Applications/QGIS-LTR.app/Contents/MacOS/../Resources/python
•	/Users/staylor1/Library/Application Support/QGIS/QGIS3/profiles/default/python
•	/Users/staylor1/Library/Application Support/QGIS/QGIS3/profiles/default/python/plugins
•	/Applications/QGIS-LTR.app/Contents/MacOS/../Resources/python/plugins
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/rasterio-1.1.5-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/matplotlib-3.3.0-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/click_plugins-1.1.1-py3.8.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/geopandas-0.8.1-py3.8.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/affine-2.3.0-py3.8.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/snuggs-1.4.7-py3.8.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python38.zip
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/cftime-1.2.1-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/numpy-1.20.1-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/numba-0.50.1-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/Pillow-7.2.0-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/Fiona-1.8.13.post1-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/lib-dynload
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/statsmodels-0.11.1-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/GDAL-3.2.1-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/patsy-0.5.1-py3.8.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/netCDF4-1.5.4-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/scipy-1.5.1-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/pandas-1.1.0-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/opencv_contrib_python-4.3.0.36-py3.8-macosx-10.13.0-x86_64.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/Rtree-0.9.4-py3.8.egg
•	/Applications/QGIS-LTR.app/Contents/MacOS/lib/python3.8/site-packages/pyproj-2.6.0-py3.8-macosx-10.13.0-x86_64.egg
•	/Users/staylor1/Library/Application Support/QGIS/QGIS3/profiles/default/python
D:\eclipse\plugins\org.python.pydev.core_7.0.3.201811082356\pysrc


How do I fix this?
fossiltx/fossiltx is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
