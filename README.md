# xbee-pyboard-skin
XBee MicroPython Skin for pyboard

<h4>Background</h4>
The <a href="http://micropython.org">MicroPython project</a> created a reference design called the "<a href="http://docs.micropython.org/en/latest/pyboard/pyboard/quickref.html">pyboard</a>" that includes an ARM processor with USB connectivity, button and switch I/O, access to all pinouts and SD card storage. The pyboard layout accepts daughterboards, called "skins" including a couple official ones that support <a href="https://micropython.org/store/#/products/LCD32MKv1_0">LCD screens</a> and <a href="https://micropython.org/store/#/products/AMPv1_0">Audio</a>.

<h4>XBee Skin</h4>
The XBee Skin for MicroPython connects any through-hole XBee module directly to the reference pyboard. It supports the XBee's association indicator and RSSI signal strength output lights, and features a more conveniently positioned reset button for the pyboard itself.

Building the board requires two off-the-shelf components:
<ul>
<li><a href="https://www.sparkfun.com/products/116">0.1" male breakaway headers</a></li>
<li><a href="https://www.sparkfun.com/products/8272">2mm 10-pin female headers</a> used as the XBee socket</li>
</ul>

Printed circuit boards can be ordered from <a href="https://oshpark.com/shared_projects/8GL4dNoX">OSH Park</a>.
