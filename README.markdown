
## Flam3 Fork - Mac OS X Specific
This source repository is a clone of the main Flam3 source repository found at:<br/> 
<a href="http://code.google.com/p/flam3/source/checkout">Flam3 - the original main repository</a>.<br/>
 Its a fork from version 3.0.1 of the original Flam3 source repository.

### Mission
The mission of this repository is to be a place for Mac OS X specific customizations, so that Flam3 can be used in Mac environments unsuitable for the generic OS independent Flam3. It also provides convenient downloads for Mac OS X prebuilt binaries and any Xcode projects used to build Flam3.

If you want the original Flam3 source code repository and web site, please go to: <br/><a href="http://code.google.com/p/flam3">Flam3 - the original main repository</a>.<br/> If you want to use Flam3 on Linux, Windows, Solaris, etc., please go to that link as well.

### License
Flam3 is licensed under <a href="http://www.gnu.org/licenses/gpl-3.0.html">GNU Public License version 3</a>. The original author is Scott Draves. Erik Reckase has been a frequent contributor to the project too. It is a very stable program and can be considered the reference Flame algorithm renderer.

    FLAM3 - cosmic recursive fractal flames
    Copyright (C) 1992-2009 Spotworks LLC

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

###Pre-built Binaries For Mac Snow Leopard and Lion
A convenient binary download Zip file for the Flam3  executables and the flam3-palettes.xml.

###Flam3 Documentation
See <a href="http://code.google.com/p/flam3/wiki/Introduction">Flam3 Project Website</a>.

### Mac Specific Customization
The original Flam3 project is quite portable among Unix derived operating systems (Mac OS X is derived from BSD Unix). However, some recent Mac specific updates, for instance, application sandboxing under Mac Lion, make the original Flam3 command line executables unusable as a plugin Flame renderer to a sandboxed client application. 

This Github hosted project will experiment with a new server implementation of Flam3 using Apple's XPC library. This new server flam3-render-svr will be a separate executable from flam3-render, so that normal command line usage of the orignal flam3-render is unchanged.

Disclaimer: Its not known whether under Sandboxing, that an Flam3 XPC server can be used as a *launchd* and *XPC* compatible plugin style server for sandboxed client applications. We will find out.

