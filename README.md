British Library Crowdsourced Tagging
==============

A [WorkMachine](https://github.com/abhiyerra/workmachine/) workflow to
tag the British Library
[images released on Flickr](http://www.flickr.com/photos/britishlibrary/). Help
curate and tag the images.

Running
===============

This is a project written in go so the best way to run it is to run

    go run british_library_tag.go -in_file in_file.csv

or complie the app

   go build
   ./british_library_tag -in_file in_file.csv

The files are in lists. This will eventually make use of the
imagedirectory and have more relavent information.


LICENSE
===============

The MIT License (MIT)

Copyright (c) 2013 Abhi Yerra

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
