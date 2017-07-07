
# USBMON
USBMON is a small script to monitor when a USB device is put in and sends a notification including the loaded drivers for all interfaces.  
Therefore it might raise awareness if something phishy is going on.

![USBMON-Screenshot](usbmon.png)

## INSTALL
It runs on Gnome Shell on Ubuntu. Feel free to test and report.
USBMON is build on pyudev:

```sh
sudo apt install python3-pyudev
```

To start USBMON at login,
start `gnome-session-properties` and add `usbmon` to the startup applications.

## LICENSE

MIT License

Copyright (c) 2017 73

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
