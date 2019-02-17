<p >
  <img src="https://raw.githubusercontent.com/polichan/RootlessInstaller/master/Screenshot/Icon.png" alt="RootlessInstaller" title="RootlessInstaller" height=100px>
</p>

# RootlessInstaller
This project can install unpatched DEB files on iOS, and it's strictly for tweaks.

# Screenshot
Launchscreen|Main
------------ | ------------- 
![pic1][1]|![pic2][2]



# Usage
Once you install this application via Cydia Impactor or something of the sort, SSH into your device and run the following command:
```bash
$(find /var/containers/Bundle/Application | grep RootlessInstaller.app/install.sh)
```

# Credits

* icons by [LuMartti][3]
* Forked from [Alticha][4]
* Launchscreen by [PoliChan][5]


  [1]: Screenshot/1.png
  [2]: Screenshot/2.png
  [3]: http://twitter.com/LuMartti
  [4]: https://github.com/Alticha
  [5]: https://github.com/polichan
