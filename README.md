## Archiving

(June 29, 2021) This project is no longer maintained. Check out the C++ version of the same program ![here](https://github.com/jeongm-in/limsave):  

## Does not support Python 3.8
PIL, the image library used in this project, does not yet support Python 3.8. 

### Overview
  - Windows 10 by default ships with beautiful image slide shows (spotlight). 
  - This script saves spotlight so that images can be used for desktop background image.

  
### Miscellaneous Details
  - Windows 10 saves miscellaneous image files, including the files for the lockscreen slide show, in a local directory under `Users/name/AppData/Local/Packages/Microsoft.Windows.ContentDeliveryManager/_cw5n1h2txyewy/LocalState/Assets`
  - In addition to spotlight images, this folder also contains icon files for Windows app. 
  - This script will filter out any non-spotlight images and copy them to designated folder.
  
### Todo
  - Create GUI file to get rid of all the commandline interaction
  - Add feature for an one-time installation and regular automatic script execution
  
### requirements 
  - Python==3.6.7 or above | Pillow>=6.2.0
  - __Windows 10__
  
