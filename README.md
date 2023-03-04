# kng-ragdoll
**Project Description:**
>Ragdoll Script for FiveM
This ragdoll script can be used with a command, keybind or both. By default it will use the keybind "U". Both the keybind and command can be changed in the client files.


**Use Keybind:**
>Under fxmanifest.lua client_scripts make sure to use the following client file:

![Image1](https://media.discordapp.net/attachments/1047971380056043593/1081308720480391248/Screenshot_5.png)


**Use Command:**
>Under fxmanifest.lua client_scripts make sure to use the following client file:

![Image2](https://media.discordapp.net/attachments/1047971380056043593/1081308720480391248/Screenshot_5.png)


**Use Keybind and Command:**
>Under fxmanifest.lua client_scripts make sure to use the following client files:

![Image3](https://media.discordapp.net/attachments/1047971380056043593/1081308720987910285/Screenshot_7.png)


**Changing Keybind:**
>Go to cl_keybind.lua go to line 29 and change the number to a new keybind you want to use. You can go to the link and find all available keybinds at https://docs.fivem.net/docs/game-references/controls/


**Changing Command:**
>Go to cl_command.lua go to line 26 and change the command name under RegisterCommand. This can be any command you want. Make sure to not use duplicate commands that could be used by other scripts.
