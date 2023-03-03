# kng-ragdoll
Ragdoll Script for FiveM
This ragdoll script can be used with a command, keybind or both.

1. Use Keybind
Under fxmanifest.lua client_scripts make sure to use the following client file:
https://i.imgur.com/XyyTNtP.png

client_scripts {
    "cl_keybind.lua"
}


2. Use Command
Under fxmanifest.lua client_scripts make sure to use the following client file:
https://i.imgur.com/aHEtUqG.png

client_scripts {
    "cl_keybind.lua"
}


3. Use Keybind and Command
Under fxmanifest.lua client_scripts make sure to use the following client files:
https://i.imgur.com/UepyLXs.png

client_scripts {
    "cl_keybind.lua",
    "cl_command.lua"
}
