# xcode-images
Device Support Platforms for iOS / Xcode 10 9 / iOS 12.1 12.0 11.3 

Fixes problem "Could Not Locate Device Support Files" for newer iOS devices

Run the script to download and install missing Xcode Developer Support Images 



# Usage

Execute the install script

```
bash <(curl -s https://raw.githubusercontent.com/fraigo/xcode-images/master/install)
```

And select the image version to install

```
Current versions installed:
10.0		11.0		11.3 (15E5178d)	8.0		8.4		9.3
10.1		11.1		11.4		8.1		9.0		__MACOSX
10.2		11.2		12.0 (16A366)	8.2		9.1
10.3		11.3		12.1 (16B5059d)	8.3		9.2

Current versions available to install:
11.3
12.1

Which image to install? : 12.1
```

The image will be downloaded and then installed in 

```
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/
```


