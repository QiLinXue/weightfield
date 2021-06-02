# WeightField2

Weightfield2 is a freeware 2D simulator for silicon and diamond detector

It is based on Weightfield ( http://www.hephy.at/en/research/departments/semiconductor-detectors/detector-simulation )
You need to have root ( http://root.cern.ch ) on your machine

How to run Weightfield2

1) get the file and type
`make` for Linux
or
`make -f Makefile_MacOS10.10_root6` if you are running ROOT6 with MacOS10.10

1) Create a symbolic link:

`ln -s Dict_rdict.pcm   /path-to-root/lib/Dict_rdict.pcm`

3)` ./weightfield &`

Note: additional libraries and/or ROOT libraries may be required for running WF2  
For further details and manual, read wiki
