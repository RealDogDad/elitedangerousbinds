# 🚀 Elite Dangerous: Odyssey 🛰️ Keybinds for Logitech X52 Pro 🕹️ H.O.T.A.S. By 🏔️ RealDogDad 🐕
RealDogDad's HOTAS Keybinds for Elite Dangerous. Updated upon game update.
Feel free to use in your own way without credit. 👌
## Logitech X52 Pro Prerequisites:
- [x] Disable Clutch Button
- [x] Keep (or Change To) completely unprogrammed via X52 software. Located [here](https://logitechg502.com/wp-content/drivers/X52_HOTAS_x86_8_0_213_0.exe). 
## 📋 How To Use My Settings:
1. Download `RealDogDad.binds` from this repo. These Keybinds are compatible with MKB, MKB+H.O.T.A.S. or just H.O.T.A.S.
2. Rename file to your preferred name (For this guide: `[Named].binds`)
1. Navigate to `C:\Users\[YourUserName]\AppData\Local\Frontier Developments\Elite Dangerous\Options\Bindings\` in an Explorer.
2. Save `[Named].binds` to the above directory. Launch Elite Dangerous: Odyssey.
3. In Game: Navigate to Options>General Control, set the dropdown to `[Named].binds` and apply.
4. In Game: Navigate to Options>Ship Control, set the dropdown to `[Named].binds` and apply.
5. In Game: Navigate to Options>SRV Control, set the dropdown to `[Named].binds` and apply.
6. In Game: Navigate to Options>On Foot Control, set the dropdown to `[Named].binds` and apply.
7. Become the greatest Commander Elite Dangerous has ever known.
__REMEMBER:__ *Any* change to the keybinds using the Game UI will set your controls in that category to 'Custom'. It will not save to the preset `[Named].binds`
## 📋 How To Use Your Own Settings:
1. Navigate to `C:\Users\[YourUserName]\AppData\Local\Frontier Developments\Elite Dangerous\Options\Bindings\` in an Explorer.
2. Open `Custom.binds` in your favorite monospace editor like [VSCode](https://code.visualstudio.com/) or the in-browser [VSCode.Dev](https://vscode.dev/).
3. Make a copy of `Custom.binds` and name it whatever you like e.g. `[Named].binds`. This will effectively 'import' whatever settings you've tweaked in game already.
2. Save `[Named].binds` to the above directory. Launch Elite Dangerous: Odyssey.
4. In Game: Navigate to Options>General Control, set the dropdown to `[Named].binds` and apply.
5. In Game: Navigate to Options>Ship Control, set the dropdown to `[Named].binds` and apply.
6. In Game: Navigate to Options>SRV Control, set the dropdown to `[Named].binds` and apply.
7. In Game: Navigate to Options>On Foot Control, set the dropdown to `[Named].binds` and apply.
8. Become the greatest Commander Elite Dangerous has ever known.
__REMEMBER:__ *Any* change to the keybinds using the Game UI will set your controls in that category to 'Custom'. It will not save to the preset `[Named].binds`
## ☠️ Want to make your own H.O.T.A.S. Preset?:
1. Navigate to `C:\Users\[YourUserName]\AppData\Local\Frontier Developments\Elite Dangerous\Options\Bindings\` in an Explorer.
2. Open `Custom.binds` in your favorite monospace editor like [VSCode](https://code.visualstudio.com/) or the in-browser [VSCode.Dev](https://vscode.dev/).
3. Make a copy of `Custom.binds` and name it whatever you like e.g. `[Named].binds`. This will effectively 'import' whatever settings you've tweaked in game already. 
4. On Win11: Open Settings>Bluetooth & Devices>More Devices & Printing Settings. 
5. Right-Click on your input controller (Pedals, HOTAS, Joystick) and select Properties.<picture><source media="(prefers-color-scheme: dark)" srcset="https://i.ibb.co/PYdS3TZ/Controller-Properties.png" alt="Controller-Properties"><img alt="Windows 11X52 Professional HOTAS Properties Screen" src="https://i.ibb.co/PYdS3TZ/Controller-Properties.png"></picture>
6. The screen above will help label each individual input for use in the `.binds` file. The `.binds` file seems to be in a rough XML format for those familiar.
7. An 'Action' Tag can be used to assign an action to a key. Use `<YawLeftButton>...</YawLeftButton>`.
7. Use `<Primary Device="Keyboard" Key="Key_J"/>` to assign an input to as the primary means to trigger the 'Parent' action.
9. To use multikey commands use the `<Modifier>...</Modifier>` tag inside of a Primary or Secondary tag.
8. E.g. 
```
<TargetWingman0>
	<Primary Device="Keyboard" Key="Key_8" />
	<Secondary Device="SaitekX52Pro" Key="Joy_23">
	  <Modifier Device="SaitekX52Pro" Key="Joy_16" />
	</Secondary>
</TargetWingman0>
```
9. Keep in mind, you can assign more than one command to one keystroke. This may be prohibitive In Game, as such, consider the following: Keybinds in different 'Modes' __Can__ overlap, Keybinds in the same 'Mode' __Cannot__. 'Modes' in this context is flight (excluding landing), SRV, UI/Menu, and On Foot.

A Big 👍Thanks👌 to [andrewdsmith](https://github.com/andrewdsmith) for the [EDXLC](https://github.com/andrewdsmith/edxlc) a companion app for status lights on H.O.T.A.s. for Elite Dangerous.
And A Big 👍Thanks👌 to [troynt](https://github.com/troynt) for the [Elite Dangerous Controls Reference](https://troynt.github.io/elite_dangerous_controls_reference/)
### I hope this guide and associated files help another Commander or two. ☄️ See you in the Void, Commander 🌌
