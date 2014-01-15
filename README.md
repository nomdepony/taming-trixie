Taming Trixie
==============

WARNING: MATURE CONTENT FOR MATURE ADULTS ONLY

Copyright nomdepony <nomdepony@gmail.com>

Built using Twine ( http://twinery.org/ )
and SugarCube ( http://www.motoslave.net/sugarcube/ )

The game is nowhere complete, and is currently quite broken.  
If you want to see example gameplay, try the demo, http://www.mediafire.com/download/u5pmym9kouzsgyi/tt_demo.zip

Q: I want to contribute by writing.  
A: Check with me about what you want to write, then read SCENES.md and send me your text. I can take care of the Twine specific parts.

Q: I want to build my own copy.  
A: Are you using Windows, OS X, or Linux?

For Windows/OSX.  
Install Twine. Go find Twine's installation, and in the folder 'targets'
make a new folder called 'Sugarcube'. Unzip the Sugarcube file in there.  
Open 'taming_trixie.tws' in Twine and pick Build, Test Play from the menu.

For OSX/Linux.  

    git clone https://github.com/tweecode/twine.git
    
Install wxPython  

    mkdir twine/targets/Sugarcube
    cd twine/targets/Sugarcube
    
Download SugarCube and unzip the file there

To build, go to the Taming Trixie git directory.  

    ~/whereyouputtwine/twee -t Sugarcube tt_main.twee tt_settings.twee tt_scenes.twee tt_training.twee tt_endings.twee > taming_trixie.html
