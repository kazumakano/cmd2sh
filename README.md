# cmd2sh
With this package, you can use some reproduced Linux/Unix shell commands on Windows command prompt.

## Contents
This package includes following commands:
- cat
- cd
- clear
- cp
- grep
- ifconfig
- ls
- mv
- open
- pwd
- rm
- wc

## Installation
1. Clone this repository or download zip file.
2. Move this directory to your home directory.
3. Execute `shrc.cmd` in order to load macros and add path to this directory into your Path environment variable temporaliry.

You don't need to execute `shrc.cmd` if you set the link of Command Prompt as following:
```cmd
cmd.exe /k %USERPROFILE%\cmd2sh\shrc.cmd
```
