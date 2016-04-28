# xbee-pyboard-skin
XBee MicroPython Skin for pyboard

<h4>Background</h4>
The <a href="http://micropython.org">MicroPython project</a> created a reference design called the "<a href="http://docs.micropython.org/en/latest/pyboard/pyboard/quickref.html">pyboard</a>" that includes an ARM processor with USB connectivity, button and switch I/O, access to all pinouts and SD card storage. The pyboard layout accepts daughterboards, called "skins" including a couple official ones that support <a href="https://micropython.org/store/#/products/LCD32MKv1_0">LCD screens</a> and <a href="https://micropython.org/store/#/products/AMPv1_0">Audio</a>.

<h4>XBee Skin</h4>
The XBee Skin for MicroPython connects any through-hole XBee module directly to the reference pyboard. It supports the XBee's association indicator and RSSI signal strength output lights, and features a more conveniently positioned reset button for the pyboard itself.

<h4>Pinouts</h4>

The skin can be mounted in two different orientations, covering either the pyboard's "Y" or "X" set of pins. If you choose the "Y" pins it uses UART 6 and it you choose the "X" pins it uses UART 4.

<table>
  <tr>
    <th>Pin</th>
    <th>function</th>
    <th>pyboard</th>
    <th></th>
    <th>Pin</th>
    <th>function</th>
    <th>pyboard</th>
  </tr>
  <tr>
    <td>1</td>
    <td>RX</td>
    <td>Y1 or X1 (UART 6 or 4)</td>
    <td></td>
    <td>16</td>
    <td>n/c</td>
    <td></td>
  </tr>
  <tr>
    <td>2</td>
    <td>TX</td>
    <td>Y2 or X2 (UART 6 or 4)</td>
    <td></td>
    <td>15</td>
    <td>3.3V</td>
    <td>3.3V</td>
  </tr>
    <tr>
    <td>3</td>
    <td>RTS (optional)</td>
    <td>Y3 or X3</td>
    <td></td>
    <td>14</td>
    <td>GND</td>
    <td>GND</td>
  </tr>
    <tr>
    <td>4</td>
    <td>CTS (optional)</td>
    <td>Y4 or X4</td>
    <td></td>
    <td>13</td>
    <td>RESET (pyboard)</td>
    <td>RESET</td>
  </tr>
    <tr>
    <td>5</td>
    <td>n/c</td>
    <td></td>
    <td></td>
    <td>12</td>
    <td>SLEEP RQ</td>
    <td>Y12 or X12</td>
  </tr>
    <tr>
    <td>6</td>
    <td>n/c</td>
    <td></td>
    <td></td>
    <td>11</td>
    <td>STATUS (on/slp)</td>
    <td>Y11 or X11</td>
  </tr>
    <tr>
    <td>7</td>
    <td>n/c</td>
    <td></td>
    <td></td>
    <td>10</td>
    <td>n/c</td>
    <td></td>
  </tr>
    <tr>
    <td>8</td>
    <td>n/c</td>
    <td></td>
    <td></td>
    <td>9</td>
    <td>n/c</td>
    <td></td>
  </tr>
</table>

Building the board requires two off-the-shelf components:
<ul>
<li>2 - 10 pin <a href="https://www.sparkfun.com/products/116">0.1" male breakaway headers</a></li>
<li>2 - <a href="https://www.sparkfun.com/products/8272">2mm 10-pin female headers</a> used as the XBee socket</li>
</ul>

Optional components are:
<ul>
<li>2 - <a href="http://www.digikey.com/product-search/en?keywords=541-220GCT-ND">SMT 220 ohm resistors in 0603 package size</a></li>
<li>2 - <a href="https://www.digikey.com/product-search/en?keywords=511-1585-1-ND">SMT LEDs in 0603 package size</a></li>
<li>1 - <a href="https://www.sparkfun.com/products/8720">SMT tactile switch</a></li>
</ul>

Printed circuit boards can be ordered from <a href="https://oshpark.com/shared_projects/VDeE8qlG">OSH Park</a>.
