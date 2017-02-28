# To find the real length of objects in an image using the known lengths of some reference object:

-In order to determine the size of an object in an image, we performed calibration using a reference object such as coin in this case ('A4 size paper' can also be used as the reference object).

-Before running the above python code. The following software has to be installed for which the commands in Ubuntu have been provided (For other Windows any good site available online can be helpful):
  1.) 'OpenCV' libraries to be installed with respect to python :
      -> sudo apt-get install libopencv-dev python-opencv
  
  2.) 'Python scipy' library to be installed :
      -> sudo apt-get install python-scipy
   
  3.) To install pip :
       -> sudo apt-get install python-pip python-dev build-essential
       -> sudo pip install --upgrade pip
    
  4.) A special repository in github called 'imutils' used :
      -> pip install --user imutils

-After all the softwares are successfully installed, place the 'pen_size.py' file and the 'input.jpg' image into your home directory in the Ubuntu system.

-Run the following command on the terminal and after getting outputs keep pressing 'ENTER' to get the outputs:
  -> python pen_size.py --image input.jpg --width 2.3

-There are basically two runtime commands the first one is after '--image' above i.e. the image path and second one is after '--width' the width of the reference object which is 2.3cm in this case.

-For the input images, the angle with the plane of objects should be a perfect 90-degree angle “looking down” (like a birds-eye-view) at the objects or the outputs will come incorrect at times.
