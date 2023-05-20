In case the game doesn't run well, this is here to Troubleshoot, hence the name.

### Game is stuck at around 20~30FPS
- Ensure FPS++ is enabled and set to above 30 or you will be locked into this state.
- Make sure your hardware is supposed to be able to exceed 30FPS, try going into a Shrine.
- Try disabling Vsync temporarily and see if this changes the behavior

### Game feels like it's playing in Slowmotion or Fastforward
- On occasion FPS++ will incorrectly apply after starting the game. Restarting Cemu usually resolves this.
- Do not use FPS++'s Static Mode (Enabled) instead of Disabled (Default, Dynamic); Static Mode will cause this behavior.
- Changing the Frame Average to a higher value instead of using the default value 8 can also cause this issue

### Cutscenes cause the game to freeze / softlock
This can be caused by setting the framerate above 60FPS. If it still occurs at 60FPS, then set it to 30FPS or disable FPS++ temporarily, then change the setting back after the cutscene has finished, save, and then restart Cemu. Alternatively you may try using OpenGL instead of Vulkan.
