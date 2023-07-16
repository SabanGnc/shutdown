
![img_58336fa5f0d8d](https://github.com/SabanGnc/shutdown/assets/139702707/36dc7d85-6bec-4c2f-9f65-14f36b2d1939)
# shutdown

## Build
```
pyinstaller shutdown.py -F -w --version-file file_version_info.txt -n poweroff
```
### Note
If name of the exe file is shutdown, it doesn't work because the commands required to run the shutdown command and shutdown.exe are the same. Instead of turning off the computer, the shutdown.exe will turn itself on again.
