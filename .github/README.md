# Use keyboard to key in the numpad in-game - AutoUpdate Support

## Description

This branch is to support automatic updates for Use keyboard to key in the numpad in-game.  
A push to this branch triggers a GitHUB action, which re-calculates the hash of the current master branch  
and writes it into the file _meta.json_.  
The game client checks your local version against this hash.  
If it differs, it will download the zip from the provided URL and extract it into your mods directory.  

Test

## Credit:
The original code for the hash generation was made by fragtrane,  
https://github.com/fragtrane/Python-SuperBLT-Hash-Calculator

All other code was made by Kamikaze94 and partially by MrDogit
https://github.com/Kamikaze94/WolfHUD/tree/autoupdate

