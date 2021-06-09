# Opencore_Dell_5448
| Feature | Status | Notes |
| ------------- | ------------- | ------------- |
| **Backlight Controls** | ✅ Working |  |
| **Battery** | ✅ Working |  |
| **imessage, app store, etc.** | ✅ Working |  |
| **All 3 usb ports** | ✅ Working |  |
| **Keyboard** | ✅ Working |  |
| **Trackpad** | ✅ Working |  |
| **Ethernet** | ✅ Working |  |
| **Webcam** | ✅ Working |  |
| **HDMI** | ✅ Working |  |
| **Graphics** | 🔶 Only Intel HD Graphics 4400 |  |
| **Amd r7 m265** | ❌ Not working |  |
| **Speakers and Headphones** | ✅ Working | Any distortion try switching audio output to either left or right |
| **Wi-Fi/BT** | 🔶 Working, Need to add kext | Link is below for the wifi and bluetooth kext |


### 🔈 Audio
By default, the audio can be a bit buggy. When using headphones, after some time the audio randomly stops. Sometimes un- and replugging the headphones works, but that's pretty annoying and unreliable. To permanently fix this issue you will have to install [ComboJack](https://github.com/hackintosh-stuff/ComboJack/tree/master/ComboJack_Installer) from the ```tools``` folder by running `install.sh`.

### 📶 Wi-Fi/Bluetooth
https://github.com/OpenIntelWireless/itlwm

### Shutdown/Sleep/Restart
This issues was fixed! Check the [**Management-Engine-Firmware**](https://github.com/anhbinhvodanh/Dell-5547-Hackintosh/tree/master/Management-Engine-Firmware) folder!
