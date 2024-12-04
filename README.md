##Not mine, just a repost.
Full credit to- https://github.com/ykeara
https://github.com/JoeLudwig
## Bindings

|    Action     |     Type      |  Explanation  |
| ------------- | ------------- |  ------------ |
| Play Next Track | Binary/Button | The same as using the media keys. Tells a media player to play the next song.|
| Play Previous Track | Binary/Button | The same as using the media keys. Tells a media player to play the previous song. |
| Pause/Play Track | Binary/Button | The same as using the media keys. Tells the media player to press play/pause. |
| Stop Track| Binary/Button | The same as using the media keys. Tells the media player to stop playback. |

### Motion

Actions associated with motion tab, and motion.

Override actions will take priority over non-override actions during simultaneous activation. Example: binding space turn to single click and space drag (override) to double click on the same physical button.

|    Action     |     Type      |  Explanation  |
| ------------- | ------------- |  ------------ |
| Left Hand Space Turn | Binary/Button | Rotates PlaySpace based on left controller rotation while held. |
| Right Hand Space Turn | Binary/Button | Rotates PlaySpace based on right controller rotation while held. |
| Left Hand Space Drag | Binary/Button | Moves PlaySpace based on left controller position while held. |
| Right Hand Space Drag | Binary/Button | Moves PlaySpace based on right controller position while held. |
| (Optional Override) Left Hand Space Turn | Binary/Button | Override version: will activate instead of non-override during simultaneous activation. |
| (Optional Override) Right Hand Space Turn | Binary/Button | Override version: will activate instead of non-override during simultaneous activation. |
| (Optional Override) Left Hand Space Drag | Binary/Button | Override version: will activate instead of non-override during simultaneous activation. |
| (Optional Override) Right Hand Space Drag | Binary/Button | Override version: will activate instead of non-override during simultaneous activation. |
| Swap Active Space Drag to Left Hand (Override) | Binary/Button |  Activates space drag on left controller only if right controller is currently active in space drag. (Useful for climbing motions) |
| Swap Active Space Drag to Right Hand (Override) | Binary/Button | Activates space drag on right controller only if left controller is currently active in space drag. (Useful for climbing motions) |
| Gravity Toggle | Binary/Button |  Toggles Gravity state when pressed. |
| Gravity Reverse | Binary/Button |  Temporarily Reverses Gravity while held. |
| Reset Offsets | Binary/Button |  Resets your offset and rotation to 0. |
| Apply Offsets | Binary/Button | Recalibrates center/rotation from offsets |
| Height Toggle | Binary/Button |  Shifts the gravity floor level by offset configured in motion tab. If gravity is inactive: also shifts the user's current y-axis position by offset configured in motion tab. |
| Snap-Turn Left | Binary/Button |  Rotates a set value to the left based on settings in motion tab. |
| Snap-Turn Right | Binary/Button |  Rotates a set value to the right based on settings in motion tab. |
| Smooth-Turn Right | Binary/Button | Rotates an amount per frame to the right based on settings in motion tab. |
| Smooth-Turn Left | Binary/Button | Rotates an amount per frame to the left based on settings in motion tab. |
| Auto-Turn Toggle | Binary/Button | Toggles the Auto-Turn Feature on/off.

### Misc.

Actions that don't have a clear category.

|    Action     |     Type      |  Explanation  |
| ------------- | ------------- |  ------------ |
| X-Axis Lock Toggle | Binary/Button | Toggles the lock of the X-Axis for offsets.|
| Y-Axis Lock Toggle | Binary/Button | Toggles the lock of the Y-Axis for offsets.|
| Z-Axis Lock Toggle | Binary/Button | Toggles the lock of the Z-Axis for offsets.|
| Chaperone Toggle | Binary/Button | Toggles the chaperone on/off. |
| Keyboard Shortcut One | Binary/Button | Sends the key sequence defined the the settings file. Defaults to Ctrl+Shift+M (Discord default toggle mute). |
| Keyboard Shortcut Two | Binary/Button | Sends the key sequence defined the the settings file. This has no default sequence. |
| Keyboard Shortcut Three | Binary/Button | Sends the key sequence defined the the settings file. This has no default sequence. |
| Key Press Misc | Binary/Button | Sends the key press defined in the settings file. Defaults to F9 |


### System.

Actions That will stay active regardless of the situation.


|    Action     |     Type      |  Explanation  |
| ------------- | ------------- |  ------------ |
| Push to Talk | Binary/Button |  Acts as starter for PTT, can mute if push-to-mute is selected.|
| Add Left Haptic Click | Binary/Button | simulates a "click" with controller haptics. (left hand)
| Add Right Haptic Click | Binary/Button | simulates a "click" with controller haptics. (right hand)
| Key Press System | Binary/Button | Sends the key press defined in the settings file. Defaults to F9 |
| Exclusive Input Toggle | Binary/Button | Switches between App and OVRAS keybinds, *note:* OVRAS's system Key-Binds remain active all the time

### Haptics.

These Actions are Hidden, They are bound by default. They allow the application to use the haptics and proximity sensor in HMD's.

|    Action     |     Type      |  Explanation  |
| ------------- | ------------- |  ------------ |
| Haptics Left | Vibration | Handle for haptic events on the Left Controller. **Do not "bind" this action**|
| Haptics Right | Vibration | Handle for haptic events on the Right Controller. **Do not "bind" this action**|
| Proximity Sensor | Binary/Button | Connects Automatically to your HMD's proximity sensor. **Do not "bind" this action**, it will cause un-predictable behavior. |


## Default Bindings

### Vive Wands

- Menu Button (both hands)
  - **Single Click**: Space Turn (respective hand)
  - **Double Click**: Space Drag (override) (respective hand)
  - **Single Click**: Swap Active Space Drag (override) (respective hand)
- TrackPad (right hand)
  - **D-pad Down click**: Push-to-Talk
- Haptics bound

### Valve Index Controllers (Knuckles)

- B Button (both hands)
  - **Single Click**: Space Turn (respective hand)
  - **Double Click**: Space Drag (override) (respective hand)
  - **Single Click**: Swap Active Space Drag (override) (respective hand)
- Trigger (left hand)
  - **Click**: Push-to-Talk
- Haptics bound

### WMR

- Menu Button (both hands)
  - **Single Click**: Space Turn (respective hand)
  - **Double Click**: Space Drag (override) (respective hand)
  - **Single Click**: Swap Active Space Drag (override) (respective hand)
- TrackPad (right hand)
  - **D-pad Down click**: Push-to-Talk
- Haptics bound

### Touch
- B/Y Button (respective hands)
  - **Single Click**: Space Turn (respective hand)
  - **Double Click**: Space Drag (override) (respective hand)
  - **Single Click**: Swap Active Space Drag (override) (respective hand)
- Trigger (left hand)
  - **Click**: Push-to-Talk
- Haptics bound

