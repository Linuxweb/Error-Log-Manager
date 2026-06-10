# Error Log Remover
This plugin is used to find all error logs in the /home directory where the user can then view them in ConfigServer Explorer, or delete them entirely.

## Features
- The plugin will automatically detect whether you are running FPM or Legacy and find the files accordingly.
- If you have ConfigServer Installed, you can navigate to the file directory through the plugin.
- A whole lotta fun.

---

## Installation Steps
1. First, you'll need to download `errorlogmanager.tar.gz` from this repository.
2. Upload that script to `/usr/src` on your device or server.
3. To navigate to that directory and uncompress the file, use the command `cd /usr/src && tar -xzf errorlogmanager.tar.gz`.
4. Now install the plugin `cd errorlogmanager && ./install.sh`.

You should now see that the plugin has been installed, and is available under "Plugins".

## Uninstall
To uninstall this plugin, simply use the command `/usr/src/errorlogmanager && ./uninstall.sh`. This will delete the compressed file as well as the installed plugin.

---

## ! Disclaimer !
Even though we have tested the safety of this software, using this plugin will be at your own risk and Linuxweb will not be held responsible in a case of lost data or any other damagae. This plugin gives you the ability to delete files in mass and requires great care.
