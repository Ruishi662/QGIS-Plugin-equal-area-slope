Plugin Builder Results

Your plugin EA_Slope was created in:
    C:/Users/s4340789/Desktop/QGIS_Plugins\ea_slope

Your QGIS plugin directory is located at:
    C:/Users/s4340789/AppData/Roaming/QGIS/QGIS3/profiles/default/python/plugins

What's Next:

  * Copy the entire directory containing your new plugin to the QGIS plugin
    directory

  * Compile the resources file using pyrcc5

  * Run the tests (``make test``)

  * Test the plugin by enabling it in the QGIS plugin manager

  * Customize it by editing the implementation file: ``EA_Slope.py``

  * Create your own custom icon, replacing the default icon.png

  * Modify your user interface by opening EA_Slope_dialog_base.ui in Qt Designer

  * You can use the Makefile to compile your Ui and resource files when
    you make changes. This requires GNU make (gmake)

For more information, see the PyQGIS Developer Cookbook at:
http://www.qgis.org/pyqgis-cookbook/index.html

(C) 2011-2018 GeoApt LLC - geoapt.com


This plugin was developed from the plugin "Equal Area Slope Estimator" in QGIS 2.18, with the same method implemented in the solver.
Care must be taken from following aspects:

1) Vector and raster layers must be in the same coordinate reference systems
2) Vector layer must be in the extent of the raster layer