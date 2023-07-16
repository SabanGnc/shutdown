# shutdown
shutdown pc use python
When I shut down my Windows device normally, it wouldn't shut down completely.
I useing .bat file but change all time timing.
In this file, I can set the time as I want and it also uses a gui.
## Build
```
pyinstaller shutdown.py -F -w --version-file file_version_info.txt -n poweroff
```
### Note
If name of the exe file is shutdown, it doesn't work because the commands required to run the shutdown command and shutdown.exe are the same. Instead of turning off the computer, the shutdown.exe will turn itself on again.
