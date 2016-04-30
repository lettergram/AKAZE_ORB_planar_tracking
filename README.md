AKAZE and ORB planar tracking
=====

Taken [directly from openCV tutorials](http://docs.opencv.org/3.0-beta/doc/tutorials/features2d/akaze_tracking/akaze_tracking.html).

Only added cmake file, commands, and files.

#### To Run:

	$ mkdir build && cd build
	$ cmake ..
	$ make
	$ ./planar_tracking ../blais/blais.mp4 result.avi ../blais/blais_bb.xml.gz