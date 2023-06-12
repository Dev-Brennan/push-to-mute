# push-to-mute
This autohotkey script is designed to create the push to mute functionality in the Windows Xbox Game Bar for use while streaming through OBS.

1. Assign F8 to the foot pedal or stream deck button you wish to use for your push-to-mute button.
2. Go into the Xbox Game Bar, enable push to talk, and change your push-to-talk shortcut to be your foot pedal, so it should say F8, and save.
3. Download https://www.autohotkey.com/ and just do the regular install. You can exit out of this once installation is complete.
4. Place the attached file on your desktop (or any safe location that you can remember).
5. Double click on the file to run the script. You will notice in the taskbar that there's a new icon, a green H. If you hover over this, it will say push-to-mute.ahk. This means that the script is running.
6. Join an Xbox party through the Xbox Game Bar. You may or may not be muted initially. Just press your mute button from before and release it. You should now be able to speak in the party.
7. Now press and hold your mute button and you will be muted in the party, but the mic goes through to OBS.
8. Use as needed to mute your mic to Xbox party chat.
9. Right click on the green H icon and click Exit to end the script or click Suspend Hotkeys to temporarily disable your hotkey (this then turns F8 into a regular push to talk button).

Notes:
 - Keep in mind that if you have F8 assigned as a hotkey in OBS or any other part of your system, you will want to use a different button in the script or change your hotkey in OBS/system.
 - The script doesn't work when you have the game bar overlay showing. 🤷‍ The script does have the potential to break as Microsoft makes changes to game bar. I'll do my best to help you if you run into issues.
 - You need to restart the script whenever you restart your streaming PC.
