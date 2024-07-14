# Syncthing_cli_command
How to use synchting cli  through cmd Windows


If you want to use Synchting without opening the web interface, just with synchting-cli a native program integrate in Synchting. (this tuto don't talk about Syntrazor, even if we go through the installation of it, syntrazor is the desktop app which allows synchting management via desktop)

Firstly you need to determine the path of the syncthing.exe, considering that you download and install synctrazor with https://github.com/canton7/SyncTrayzor/releases/tag/v1.1.29.
The default path to the syncthing.exe is "C:\Program Files\SyncTrayzor\synchting.exe".

Considering you find the synchting executable you have to run your cmd and cd to the directory Synctrazor.

Finally the syntax of the basic command syncthing.exe -help (this command will show you the options and parameters of the command)

By example if you want to add an antoher device to your syncthing server you can type "syncthing cli config devices add --device-id $DEVICE_ID_B"

same way if you want to add a folder "syncthing cli config folders add --path <yourpath> --id $FOLDER_ID"
to share it "syncthing cli config folders $FOLDER_ID devices add --device-id $DEVICE_ID_B"
