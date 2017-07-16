
------------------------------------------------------

this directory contains the screen images & associated artefacts created during ux designs

./common  = all cross platform artefacts, these will be overwritten by contents of the ./<platform> directory during a build 

./<platform> = all platform specific artefacts



------------------------------------------------------
prototype screen image (.jpg) naming conventions 

xxyy##_<descriptivename> 
  where, 
	xx = 2 digit, zero padded number assigned to the directory in which the file is placed.
	yy = 2 digit, zero padded number assigned to the uniquely distinguishable functionality (ex: edit, add, view, delete).
	## = 2 digit, zero padded sequntial number within the unique functionality.
	<descriptivename> = self explainatory filename upto 30 characters

numbers should be assigned in multiples of 10, so that additional items can be introduced without a need to  renumber all subsequent screens.

Example:

a screen showing the video inputs in add mode could be named : 
201010_AddNewVideoinput_default.jpg

another similar screen but with the video-type dropdown being shown can ba named.
201020_AddNewVideoinput_inputtype.jpg

similarly a default view of the edit video input dialog could be named
202010_EditVideoinput_default.jpg
