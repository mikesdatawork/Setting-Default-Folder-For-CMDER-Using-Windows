![MIKES DATA WORK GIT REPO](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_01.png "Mikes Data Work")        

# Setting Default Folder For CMDER Using Windows
**Post Date: June 23, 2017**        

## Contents    
- [About Process](##About-Process)   
- [Build Info](#Build-Info)  
- [Author](#Author)  
- [License](#License)       

## About-Process

<p>If you're like me and do any amount of web work; you'll find lots of useful tools out there for the Mac or PC so you can carry out your work. In my case; I use both machines, and usually will use the Cmder console emulator for Windows.
Found Here: http://cmder.net/
Ok; so you download the .msi file, and the installation goes great, but now you want to set the default folder.
You can set the default folder with the /start switch for the short cut. Below is how I made that happen.
Go to the CMDER program files and create a short cut on the Cmder.exe file.</p>

![Set Default CMDER Folder]( https://mikesdatawork.files.wordpress.com/2017/06/image0013.png "set default cmder folder")
 
Just add the /start "C:MyFolderPath" next to the original shortcut Target. Remember to add the quotes. The path you specify will be the location where Cmder will open each and every time.
For example; I want mine to open under my Projects folder so this is what I have.
"C:Program FilesProductivityToolscmderCmder.exe" /start "C:Program FilesProductivityToolsProjects"
You could create multiple shortcuts with new /start paths, and you can simply open Cmder to a new folder for each one.

![Specify Target Location]( https://mikesdatawork.files.wordpress.com/2017/06/image002.png "Specify Target Location")
 
Next to drop your shortcuts under your System32 folder, and you have your own start-run shortcut
C:windowsSystem32

![Create CMDER Shortcuts]( https://mikesdatawork.files.wordpress.com/2017/06/image003.png "Get CMDER Shortcuts")
 
Here is my start run shortcut.

![Run Custom Shortcut]( https://mikesdatawork.files.wordpress.com/2017/06/image004.png "Use Custom CMDER Shortcut")
 
Hope this gets you started on what you need for having a default home folder. 


[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

[![Gist](https://img.shields.io/badge/Gist-MikesDataWork-<COLOR>.svg)](https://gist.github.com/mikesdatawork)
[![Twitter](https://img.shields.io/badge/Twitter-MikesDataWork-<COLOR>.svg)](https://twitter.com/mikesdatawork)
[![Wordpress](https://img.shields.io/badge/Wordpress-MikesDataWork-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)

   
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Mikes Data Work](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_02.png "Mikes Data Work")

