# djangoChannels2.0
Creates random chat room for the ALFF project.

# Common errors that I ran in to... (on windows)
I had to downgrade to python 3.6 in order to install twisted.
Twisted is a vital piece that needs to be installed correctly in order for this to work, it will try to install with <pip install channels> but ends up failing. After that, if you are following the djangoChannels tutorial, you might run into an admin error and I solved this by <pip install pywin32> and then installing the other features to get this to work. Once you get to the 2nd page of the tutorial, you don't have to install docker for this to work but you need to install redis, which luckily for us, a windows development team had made a stable version for windows users and can be downloaded from their github page at github.com/MicrosoftArchives/redis


# Paste this in settings.json for multiple terminal window options!
{
    //Terminal Configurations - Uncomment any one line to open a certain termianl type.

    // Windows Powershell Terminal Option
    "terminal.integrated.shell.windows": "C:\\windows\\Sysnative\\WindowsPowerShell\\v1.0\\powershell.exe",
    
    // Bash Terminal Option
   // "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",

    // Python Terminal Option
   // "terminal.integrated.shell.windows": "C:\\Python37\\python.exe",

    "editor.minimap.enabled": true,
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    //"python.jediEnabled": false,
    "explorer.confirmDelete": false,
    "python.linting.pylintEnabled": true,
    "[python]": {
        
    }
    //hello
}
