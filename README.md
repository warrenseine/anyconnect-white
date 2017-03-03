# Cisco AnyConnect, White!

Do you use Cisco AnyConnect for VPN? You've probably noticed that it looks awful next to all the nice monochrome icons.

It's not too hard to fix this eyesore...

![Screenshot](Screenshot.png)

### A few simple directions:

1. Download [these new images](https://github.com/warrenseine/anyconnect-white/raw/master/Resources.zip).
2. Unzip these files.
3. Open Finder and Find `Cisco AnyConnect Secure Mobility Client.app`. It's probably in your Applications folder under a Cisco folder.
4. Right-click the application and select "Show Package Contents".
5. Open the "Contents" folder, and "Resources" folder.
6. Drag the new images files into the "Resources" folder and select "Replace" for each image.
   * You may need to "Authenticate" with your password if your Applications folder is protected.
7. Quit Cisco AnyConnect and open it again.

#### Terminal directions
1. Download [these new images](https://github.com/warrenseine/anyconnect-white/raw/master/Resources.zip).
2. Assuming that your Cisco AnyConnect Secure Mobility Client app is in /Applications/Cisco, and you've downloaded Resources.zip to ~/Downloads, you can just run this:
```
    sudo unzip -j -d '/Applications/Cisco/Cisco AnyConnect Secure Mobility Client.app/Contents/Resources/' ~/Downloads/Resources.zip
```
### Caveats:

* This doesn't change the software, only the images. You may want to save a copy of the original assets.
