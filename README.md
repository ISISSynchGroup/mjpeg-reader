# MJPEG Reader

A small library to enable MJPEG streams (from IP cameras/frame-grabbers) to be displayed in LabVIEW.

![Test.vi Front Panel](../gh-pages/images/Test.gif )

Note - Only unprotected HTTP streams can be opened.

## Usage
A URL is all that is required to create the MJPEG-Reader and start reading JPEG frame data.

![Test.vi Block Diagram](../gh-pages/images/Test-vi-bd.png )

## JPEG Frame to LabVIEW Image (Pixmap) Data
The conversion from JPEG frame data to LabVIEW Pixmap is currently only supported on windows through use of .NET calls. On other OSs this task is down to you.

## Performance
The performance of this library has not been battle tested but it is .Net memory leak free (thanks Desktop Execution Trace Toolkit).

## Requirements
LabVIEW 2015 SP1
