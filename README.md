# BOTW-Guide
I couldn't be bothered helping people to get and play BOTW in the "alternative" way so I made this. Enjoy

# Downloading CEMU
Download [CEMU](https://cemu.info/releases/cemu_1.27.1.zip) and extract.
Open the Cemu.exe, where you will be greeted by a 'Getting Started' window (This only happens when you first open it)

Create a folder in a safe location named "mlc01"

Leave the "Game path" field blank for now

Click "Download community graphic packs"

Click Next

N.B The "mlc01" folder The mlc01 path stores the emulated Wii U internal memory, including:

System files and apps

Installed games, updates and DLC's

User-created save data

This should be on a storage drive that Cemu will always have access to, with lots of free space. By default, the mlc01 path will be stored in the Cemu directory.

If you delete this folder everything will be gone. If this path ever gets reset, make sure to set it again in Options -> General settings -> MLC Path

# Downloading BOTW
Download [BOTW](https://archive.org/download/nintendo-wii-u-usa-full-set-wua-format-embedded-dlc-updates/The%20Legend%20of%20Zelda%20-%20Breath%20of%20the%20Wild%20%28USA%29%20%28DLC%29%20%28v208%29.wua)
in a ROM folder, just to keep everything organised.

It's as simple as that

# Setting Up CEMU

- On the top bar, go to Options -> Input settings
- Change Emulated controller to "Wii U GamePad"
- Click on the Controller field
- Set API to "SDLController"
- Set Controller to your actual controller. If no controller appears after connecting it to your computer, try changing your controller API
- Proceed to map all your controller button inputs
- At the top, enter in a controller profile name, e.g. "GamePad Controller"
- Click Save

- On the top bar, go to Options -> General settings
- Press 'Add' where the Game Paths section
- Select the folder where the BOTW file is located
- Reload CEMU and the game should be there

# Optimising CEMU

- On the top bar click Options -> General settings
- Navigate to the Graphics tab
- Change the "Graphics API" to Vulkan if it is not already
- Ensure that your "Graphics Device" is set to use your most powerful GPU if your device has dual graphics
- Set "VSync" to Match emulated display (Experimental). If you use a display with variable refresh rate (G-SYNC), set this to Off instead
- Enable Async shader compiler
- Navigate to the Audio tab
- Under General, change "API" to XAudio2

# Optimising BOTW

- On the top bar, click Graphic Packs
- Check the "Installed Games" box
- On the bottom-right of the window, use the Download latest community graphic packs button
- Once the download has finished, navigate to the Mods category
- Select and enable the FPS++ checkbox

N.B. By default, this is set to 60FPS. This increases the smoothness of gameplay, however it can cause some [issues](https://wiki.cemu.info/wiki/The_Legend_of_Zelda:_Breath_of_the_Wild#Issues_arising_by_using_FPS.2B.2B_or_static_FPS.2B.2B). When these occur, simply set the limit to 30 until you've gotten beyond the point where the issue occurs.

- Minimize the mods category
- Select and enable the Graphics checkbox
- You should see a menu on the right half of the window, where you can edit graphical settings

### Aspect Ratio

The game runs at 16:9 by default. If your moniter isn't 16:9 then change it

### Resolution

Depending on how powerful your GPU is, you can change the resolution to make it higher. Run it at different resolutions to see what runs and looks the best

### Anti-Aliasing

Just leave it on default for the best of both

### Shadows

This changes the resolutions of shadows. Set it to 300% for the best quality

### Shadow Draw Distance

Set it to Very High to increase detail whil not sacrificing too much detail
