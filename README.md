# Unity-AR-Demo

A template and demo project for Unity AR. It includes both **AR face masks** and **AR 3D object placement**. The project has different scenes for each case (see below for details).

**[You can find complete Unity project folder and APK files in here.](https://drive.google.com/drive/folders/1i2yOfNnQE1zS0SvpaxxGSspGeX18gRMd?usp=sharing)** Since, GitHub has file count and size limitations, I have uploaded the project to Google Drive.

Project has been developed on Unity 2021.1.23f1. You can find package versions below. If you are facing with errors, **please check your Unity and package versions**. Please keep in my that using different versions may result with errors.

<img src="/Images/Packages.png">

Please be aware of that, **some Android devices does not support AR**. You can find the list of AR supported Android devices in [here.](https://developers.google.com/ar/devices?hl=en)


## Face Masks
Face masking scene applies masks to faces just like Snapchat etc. Mask textures are taken from [here.](https://assetstore.unity.com/packages/essentials/asset-packs/ar-face-assets-184187)

Also, one of the masks plays a video on the face as a mask. If you want to add your own video, please **flip it while importing by using inspector**. Otherwise, you will get a mirrored video on faces.

In addition, you will find a variable which is called as "Maximum Face Count" in the inspector of AR Session Origin. It changes the maximum number of faces that will be masked for iOS. However, it changes nothing for Android, because **ARCore does not support more than one face**.

<img src="/Images/Face_Mask.jpg" width="270" height="550">


## 3D Object Placement
This scene places objects in real world scenes by using AR. Project places a French battleship [Richelieu](https://en.wikipedia.org/wiki/French_battleship_Richelieu) instead of an ordinary object for more fun. Also, **you can even rotate her main turrets (the bigger turrets placed in front of the ship) and fire them.** 3D model of Richelieu is taken from [here.](https://p3dm.ru/files/boat/marine_military_equipment/11966-richelieu.html) I think that, the source of the model is [World of Warships.](https://worldofwarships.eu/en)


To place and play with ships:
1) Hold your phone in landscape position for this scene for better user experience.
2) Wait until it detects and marks planes (do not get too close to planes).
3) Once it marks planes, tap any plane to place objects.
4) You can place more objects by tapping planes or you can move placed objects by holding them.
5) Select any placed object by tapping on it.
6) You can rotate and scale the selected object by using the buttons on the bottom of the screen.
7) If you are placing Richelieu, you can rotate and fire her main turrets by using the buttons on the top of the scren.

<img src="/Images/3D_Placement_1.jpg" width="580" height="270">
<img src="/Images/3D_Placement_2.jpg" width="580" height="270">

You can use any object that you desire to be placed, however please delete Richelieu specific functions (main turret rotation and firing functions) from scripts in this case.

