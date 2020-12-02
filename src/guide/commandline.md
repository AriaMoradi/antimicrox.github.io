# Command-line usage

```
antimicrox [OPTIONS] [PROFILE]
```

## Description

* **--tray**  
  launch program in system tray only
* **--no-tray**  
  launch program with the tray menu disabled
* **-h**, **--help**  
  display this help and exit
* **-v**, **--version**  
  output version information and exit
* **--profile** _&lt;location&gt;_  
  use specified profile as default for selected controllers. Defaults to all controllers.
* **--profile-controller** _&lt;value&gt;_  
  apply configuration file to a specific controller. &lt;value&gt; can be an controller index, name, or GUID.
* **--hidden**  
  launch program without the main window
* **--unload** _[&lt;value&gt;]_   
  unload currently enabled profile(s). Value can be a controller index, name, or GUID.
* **--startSet** _&lt;number&gt;_ _[&lt;value&gt;]_  
  start joysticks on a specific set. Value can be a controller index, name, or GUID.
* **--next**  
  Advance profile loading set options.
* **-d**, **--daemon**  
  launch program as a daemon.
* **--log-level** _{debug,info,warn}_  
  Enable logging. Default: warn
* **-l**, **--list**  
  Print information about joysticks detected by SDL.
* **--map** _&lt;value&gt;_  
  Open game controller mapping window of selected controller. Value can be a controller index or GUID.
* **--eventgen** _{xtest,uinput}_  
  Choose between using XTest support and uinput support for event generation. Default: xtest.
  