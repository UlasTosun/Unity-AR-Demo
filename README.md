# Unity-AR-Demo

A template and demo project for Unity AR. It includes both **AR face masks** and **AR 3D object placement**. The project has different scenes for each case (see below for details).

You can find complete Unity project folder and APK files in here.

Project has been developed on Unity 2021.1.23f1. You can find package versions below. If you are facing with errors, **please check your Unity and package versions**. Please keep in my that using different versions may result with errors.
![Package Versions](/Images/Packages.png)

Please be aware of that, **some Android devices does not support AR**. You can find the list of AR supported Android devices in [here.](https://developers.google.com/ar/devices?hl=en)


## Face Masks
Face masking scene applies masks to faces just like Snapchat etc. Mask textures are taken from [here.](https://assetstore.unity.com/packages/essentials/asset-packs/ar-face-assets-184187)

Also, one of the masks plays a video on the face as a mask. If you want to add your own video, please **flip it while importing by using inspector**. Otherwise, you will get a mirrored video on faces.

In addition, you will find a variable which is called as "Maximum Face Count" in the inspector of AR Session Origin. It changes the maximum number of faces that will be masked for iOS. However, it changes nothing for Android, because **ARCore does not support more than one face**.

You can find an example image in images folder.


## 3D Object Placement


