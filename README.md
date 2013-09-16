# Adventures In Raspberry Pi by Carrie Anne Philbin
## Adventure 9 resources

This repository contains code required for the Adventure 9 project in
"Adventures in Raspberry Pi". Included code is:

* vlc.py: Python bindings to libvlc, taken from <http://git.videolan.org/?p=vlc/bindings/python.git;a=tree;f=generated;b=HEAD>
* Adafruit_CharLCD.py: a modified version of Adafruit's library for interfacing
  with 16x2 LCDs on the Pi. Taken from
  <https://github.com/adafruit/Adafruit-Raspberry-Pi-Python-Code>. The default
  GPIO pins were modified, and the file was reindented to deal with Python 3's
  more strict rules on mixed indents.

## Copyright

vlc.py is licensed under the LGPL. Below is the license header:

    Python ctypes bindings for VLC

    Copyright (C) 2009-2012 the VideoLAN team
    $Id: $

    Authors: Olivier Aubert <olivier.aubert at liris.cnrs.fr>
             Jean Brouwers <MrJean1 at gmail.com>
             Geoff Salmon <geoff.salmon at gmail.com>

    This library is free software; you can redistribute it and/or modify
    it under the terms of the GNU Lesser General Public License as
    published by the Free Software Foundation; either version 2.1 of the
    License, or (at your option) any later version.

    This library is distributed in the hope that it will be useful, but
    WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
    Lesser General Public License for more details.

    You should have received a copy of the GNU Lesser General Public
    License along with this library; if not, write to the Free Software
    Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston MA 02110-1301 USA

Adafruit_CharLCD.py is licensed under the BSD license with an extra advertising
clause:

    Adafruit's Raspberry-Pi Python Code Library
    ============
      Here is a growing collection of libraries and example python scripts
      for controlling a variety of Adafruit electronics with a Raspberry Pi
      
      In progress!

      Adafruit invests time and resources providing this open source code,
      please support Adafruit and open-source hardware by purchasing
      products from Adafruit!

      Written by Limor Fried, Kevin Townsend and Mikey Sklar for Adafruit Industries.
      BSD license, all text above and below must be included in any redistribution
      
      To download, we suggest logging into your Pi with Internet accessibility and typing:
      git clone https://github.com/adafruit/Adafruit-Raspberry-Pi-Python-Code.git
      
    ============
    Copyright (c) 2012-2013 Limor Fried, Kevin Townsend and Mikey Sklar for Adafruit Industries.
    All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are met:
        * Redistributions of source code must retain the above copyright
          notice, this list of conditions and the following disclaimer.
        * Redistributions in binary form must reproduce the above copyright
          notice, this list of conditions and the following disclaimer in the
          documentation and/or other materials provided with the distribution.
        * Neither the name of the <organization> nor the
          names of its contributors may be used to endorse or promote products
          derived from this software without specific prior written permission.

    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
    ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
    WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
    DISCLAIMED. IN NO EVENT SHALL <COPYRIGHT HOLDER> BE LIABLE FOR ANY
    DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
    (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
    LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
    ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
    (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
    SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
