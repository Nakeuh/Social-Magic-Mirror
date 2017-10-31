Folder MagicMirror : 

The folder MagicMirror contain the source of the MagicMirror project from url https://github.com/MichMich/MagicMirror.
The only difference between current MagicMirror folder and original project is the file config.js.
Every MagicMirror modules can be added or deleted as for the original project.
If you want to upgrade the MagicMirror sources. Save the current config.js file, dowload updated MagicMirror sources and place it in MagicMirror folder. Replace config.js file by the old one. Test it.

For information, the difference between this config.js file and the original one is that this one get configs from another text file, and the original one just have configs directly in it.


Folder Configuration : 

Contains a config file for every saved profiles. This config file is used to configure MagicMirror modules (color, position etc...)


Folder Scripts : 

For now : just JS tests


Installation for raspberry pi : 

I ) Clone the repo

II ) For Vocal Recognition
  // get FLAC stream from mic
 sudo apt-get install sox
 
  // nodejs v5
 curl -sL https://deb.nodesource.com/setup_5.x | sudo -E bash
 sudo apt-get install -y nodejs
 

