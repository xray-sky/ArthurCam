# ArthurCam

 ArthurCam is a simple screenshot utility for the Acorn Archimedes running
 Arthur desktop. When the camera icon in the task bar is clicked, the Arthur 
 desktop is captured and written to a sprite file.

# Loading ArthurCam

### Arthur 0.30

  * Insert a disk containing the ArthurCam files before loading the
    Arthur desktop. Any other accessories present in the Accessory
    folder on this disk will also be loaded.
                                         
### Arthur 1.20

  * After the Arthur desktop has started, double-click the Camera file
    in the Accessory folder.

 If ArthurCam was successfully loaded, there will be
 a camera icon on the right side of the task bar. 

# Using ArthurCam

 When ArthurCam is first loaded, the default filename for the saved 
 screenshot is Screen0, in the root directory of whatever is the default
 drive. The filename is incremented for each screenshot (e.g. Screen1,
 Screen2, etc.) The eleventh screenshot will be ScreenA. The counter 
 overflows after 36 screenshots; the 37th invocation of ArthurCam will 
 overwrite Screen0. On a floppy disk, this isn't so much a problem as
 it will fill long before this happens.

 The filename prefix may be changed from the default "Screen" by middle-
 clicking the Camera icon and typing in a new prefix. Setting the prefix
 causes the counter to reset to 0 (even if the prefix is not changed).
 Quitting the prefix dialog leaves both the filename prefix and counter
 unchanged.

 Theoretically screenshots could be saved to another directory by 
 making the file prefix a fully-qualified path name, but I didn't test 
 this.

# Downloading the distribution

 The current distribution of ArthurCam can be downloaded as a RiscOS .arc
 file from http://www.typewritten.org/pub/ArthurCam.arc

## ArthurCam files 

 Files included in the distribution archive:

 * `.$.Accessory.Camera` - ArthurCam Desktop Accessory (must be type &FE0!)
 * `.$.Icons.Camera`     - ArthurCam Sprite file
 * `.$.Art030_0`         - Sample Arthur 0.30 screenshot
 * `.$.Art120_0`         - Sample Arthur 1.20 screenshot
 * `.$.readme/cam`       - Read Me

# License terms

 This software is hereby placed into the public domain with no warranties,
 express or implied.

 ArthurCam v1.0 - 20161226 r.stricklin <bear@typewritten.org>
