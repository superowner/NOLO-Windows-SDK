# NOLO-Windows-SDK [中文](/README_CN.md)
- You could use either SDK listed below to develop SteamVR drivers and games that support NOLO. Both SDK provide all data from NOLO, including real-time data from headset marker, controllers and base station.\
**Notice: We no longer maintain the ZEROMQ version. You should use the USBHID version for all future game development.**

- Developers can use NOLO data to communicate with a variety of game platforms.\
NOLO's headset marker provides both position and rotation data. You can use data from NOLO if data from your Helmet-Mounted-Display(HMD)'s IMU is not stable. 

- Game developers can use NOLO to develop games on various platforms.\
Unity developers can use [Unity SDK](https://github.com/NOLOVR/NOLO-Unity-SDK) provided by NOLO.  
Native Android developers can use [Android SDK](https://github.com/NOLOVR/NOLO-Android-SDK) provided by NOLO.\
Other developers can use Windows SDK (this SDK) provided by NOLO.

#
## Getting Started
### **[NOLO-USBHID-SDK](https://github.com/NOLOVR/NOLO-Windows-SDK/tree/master/NOLOVR/NOLO_USBHID_SDK) [Instructions](/HIDGetStarted.md)**

    NOLO-USBHID-SDK reads NOLO tracking data directly through USB port.  
    In this case, you DON'T need to install NOLO PC software (NOLO-Driver-for-Windows) during development.

### [NOLO-ZEROMQ-SDK](https://github.com/NOLOVR/NOLO-Windows-SDK/tree/master/NOLOVR/NOLO_ZEROMQ_SDK) [Instructions](/GetStarted.md) (Warning: We are phasing out this version!)

    NOLO-ZEROMQ-SDK reads data from NOLO PC software via ZEROMQ network transfer protocol.  
    In this case, you'll need to install NOLO PC software (NOLO-Driver-for-Windows) during development.
    Notice that NOLO PC software acquiescently provides steamvr controller driver. 
#
## Examples
See examples [here](https://github.com/NOLOVR/NOLO-Windows-SDK/tree/master/Examples).

## Notice
- **IMPORTANT!** NOLO's coordinate system is different from that of OpenVR. Read details [here](https://github.com/NOLOVR/NOLO-Windows-SDK/blob/master/NOLOVR/NOLO_USBHID_SDK/Notice_EN.pdf)! 

## Help & Discussions
Get help and submit questions [here](https://github.com/NOLOVR/NOLO-Windows-SDK/issues).

## Release notes  
View release notes [here](https://github.com/NOLOVR/NOLO-Windows-SDK/releases).