# Test tone creator
========================

* Author:	marduk191 (<marduk191@gmail.com>)
* Created:	April 7, 2016
* Github:	<https://github.com/marduk191/tcreator>
* Zip Download:	<https://github.com/marduk191/tcreator/archive/master.zip>





#Description
-------------
A sox script written for bash to automate the creation of sine test tones

#Usage
------------
Before running the script, be sure to modify some of the variables to your use case.

* Set file format for output
filefmt="wav"
* Audio sample rate
freq="44100"
* set output folder
subdir="output"
* Duration of tracks
trdur="1"
* from first frequency to end frequency
for f in {1..44100}

Then run:
````
./tcreator
````
And it should start generating your files

#Questions, Comments, Concerns, Issues
-------------------------------------
If you have any of these, go ahead and [submit an issue](https://github.com/marduk191/tcreator/issues),

#Notes
--------------------------------------
I do not suggesting running this at defaults because it will generate 44,100 files of 1 second sine noise (one for each frequency)