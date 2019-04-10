ofxWMFVideoPlayer
========================

This addon is an accelerated video player using the Windows Media Foundation API. 
It was developed by Philippe Laulheret for [Second Story] (http://www.secondstory.com) and is released under MIT licensing. See license.md for more details. 
For a more comprehensive/technical description of the work, please refer to the file TechnicalDescription.md

This addons is meant to work with openFrameworks 0.8 and superior, on windows Vista and following.
Previous version of oF should work as well but won't be maintained.

##Prerequisites 

Originally, this addon required replacing the GLEW OpenFrameworks libraries with the ones provided here. However, as of OFv10, this no longer seems necessary. The newest GLEW libraries also provide the additional benefit of supporting both x64 (64 bit) and x86 (32 bit) architectures, while those provided here only support x86.

On top of that this addon is built against the Direct X SDK of June 2010. You'll need to install it to have the headers required for compiling the example. At the time of writing, you can download it on the [Microsoft website](http://www.microsoft.com/en-us/download/details.aspx?id=6812)


##Using the example

Make sure your graphic driver is up to date.
Copy (and rename) a mp4 file as "test.mp4" into the data folder and run the example.


##Compatibility 

The texture sharing we are using is based upon an NVIDIA extension but AMD/ATI cards claims they support it was well, even though sometimes it gets more finicky.
Feedback on working/not working cards and drivers are more than welcomed.


