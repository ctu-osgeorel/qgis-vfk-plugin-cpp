VFK plugin for <a href="http://qgis.org">QGIS</a>

To compile

<pre>
cd src/plugins
git clone git@github.com:CTU-in-Prague-OSGeoREL/qgis-vfk-plugin.git vfk
</pre>

Add following to <tt>src/plugins/CMakeLists.txt</tt>:
<pre>
SUBDIRS (vfk)
</pre>

Additional info at (in Czech): http://freegis.fsv.cvut.cz/gwiki/VFK_/_QGIS_plugin
