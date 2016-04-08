# xbee-pyboard-skin
XBee MicroPython Skin for pyboard

<h4>Background</h4>
The <a href="http://micropython.org">MicroPython project</a> created a reference design called the "<a href="http://docs.micropython.org/en/latest/pyboard/pyboard/quickref.html">pyboard</a>" that includes an ARM processor with USB connectivity, button and switch I/O, access to all pinouts and SD card storage. The pyboard layout accepts daughterboards, called "skins" including a couple official ones that support <a href="https://micropython.org/store/#/products/LCD32MKv1_0">LCD screens</a> and <a href="https://micropython.org/store/#/products/AMPv1_0">Audio</a>.

<h4>XBee Skin</h4>
The XBee Skin for MicroPython connects any through-hole XBee module directly to the reference pyboard. It supports the XBee's association indicator and RSSI signal strength output lights, and features a more conveniently positioned reset button for the pyboard itself.

Pinouts
Pin
function
 
Pin
function
1	RX	 	16	n/c
2	TX	 	15	3.3V
3	RTS (optional)	 	14	GND
4	CTS (optional)	 	13	RESET (xbee)
5	n/c	 	12	SLEEP RQ
6	n/c	 	11	STATUS (on/slp)
7
n/c	 	10	n/c
8	n/c	 	9	n/c

<table>
  <tr>
    <th>Pin</th>
    <th>function</th>
    <th></th>
    <th>Pin</th>
    <th>function</th>
  </tr>
  <tr>
    <td>1</td>
    <td>RX</td>
    <td></td>
    <td>16</td>
    <td>n/c</td>
  </tr>
  <tr>
    <td>2</td>
    <td>TX</td>
    <td></td>
    <td>15</td>
    <td>3.3V</td>
  </tr>
    <tr>
    <td>3</td>
    <td>RTS (optional)</td>
    <td></td>
    <td>14</td>
    <td>GND</td>
  </tr>
    <tr>
    <td>4</td>
    <td>CTS (optional)</td>
    <td></td>
    <td>13</td>
    <td>RESET (xbee)</td>
  </tr>
    <tr>
    <td>5</td>
    <td>n/c</td>
    <td></td>
    <td>12</td>
    <td>SLEEP RQ</td>
  </tr>
    <tr>
    <td>6</td>
    <td>n/c</td>
    <td></td>
    <td>11</td>
    <td>STATUS (on/slp)</td>
  </tr>
    <tr>
    <td>7</td>
    <td>n/c</td>
    <td></td>
    <td>10</td>
    <td>n/c</td>
  </tr>
    <tr>
    <td>8</td>
    <td>n/c</td>
    <td></td>
    <td>9</td>
    <td>n/c</td>
  </tr>
</table>

Building the board requires two off-the-shelf components:
<ul>
<li><a href="https://www.sparkfun.com/products/116">0.1" male breakaway headers</a></li>
<li><a href="https://www.sparkfun.com/products/8272">2mm 10-pin female headers</a> used as the XBee socket</li>
</ul>

Printed circuit boards can be ordered from <a href="https://oshpark.com/shared_projects/8GL4dNoX">OSH Park</a>.
