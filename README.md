# Ctrl F For Goodies
random links that helped me that I will almost certainly use again 100x,
no order or logical layout for this one.

**Kill process running on a specific port.**
```
kill port, process port: https://stackoverflow.com/questions/11583562/how-to-kill-a-process-running-on-particular-port-in-linux
```

**cmdline-tools flutter error with flutter doctor**
```
https://www.youtube.com/watch?v=_ZUIUaVBIao&t=231s
```

**PATH FLUTTER ANDROID STUDIO**
```
### PATH ###

# Flutter
export FLUTTER="$PATH:/home/rick/dev/flutter/bin"

#Android Studio
export ANDROID_STUDIO="$PATH:/home/rick/dev/android-studio/bin"
export ANDROID_HOME="/home/rick/Android/Sdk"
export ANDROID_TOOLS="/home/rick/Android/Sdk/tools"
export ANDROID_PLATFORM_TOOLS="/home/rick/Android/Sdk/platform-tools"
PATH=$FLUTTER:$ANDROID_HOME:$ANDROID_TOOLS:$ANDROID_PLATFORM_TOOLS:$ANDROID_STUDIO
```

**symlink**
```
Two ways. First you can symlink studio.sh to android-studio by running 
sudo ln -s /usr/bin/android-studio /home/<user>/dev/android-studio/bin/studio.sh
 or by symlinking studio.sh to android-studio and then adding the path to your path variable. You would do this by running 
ln -s /home/<user>/dev/android-studio/bin/android-studio /home/<user>/dev/android-studio/bin/studio.sh
 and then running 
export PATH=~/dev/android-studio/bin:$PATH
 add the last command I told you to enter to your ~/.bashrc to have that persistent. I do prefer the second method over the first because it allows you to run all of the commands that are in that directory as well
```
