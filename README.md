Cool CSS3 Borders v1
===========

A small plugin for Compass to create coll CSS3 Borders with one line of code

Inspired by [jQuery Kill Photoset](https://github.com/chriskalani/Kill-Photoset/blob/master/jquery.killphotoset.js/) 

![screenshot](http://f.cl.ly/items/2w0p1A3Z3d2v3f0u0F2E/demo.png)


Example usage
=================

Include the file `_cool_border_scss` into your project. Make a reference to this file inside your style.scss.


	img{@include cool_border(color, border-raidius, padding)}
	
	img.black{@include cool_border(#222, 2px, 10px)}


The plugins takes 3 parameters only:

* Main color
* border-radius
* padding


Demo
====

A very primitive demo can be found [here](http://a00.com.ar/css3-borders/)


Licence
=======

    Copyright © 2011 Alexis Sgavel (http://github.com/Baires)
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
    
    
    