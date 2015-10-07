# run-one
Bash script that runs one app based on the executable file only

**dependency**

This script needs xdotool, wmctrl, and bash
using ```apt-get install xdotool wmctrl should work```

**Why not use run-one ?**

run-one is actually based on arguments as well as the program name.
This is enoying if you just need to use to progam to launch one instance.
Also run-one does not bring the window to front.

This script intend is to fill the gaps of run-one.

**How it works ?**

This is based on xdotool, if the window is found, the it may be used, otherwise it launches with your arguments.

**Usage**

```run-single options program programoptions```
eg : ```run-single -s -n firefox http://spacelamb.12wave.com/```

