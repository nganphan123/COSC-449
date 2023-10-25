# COSC-449

Honours thesis regarding eye-tracking applications:

1. Desktop-based application with Tobii device

2. AR application on MetaQuest headset

## Progress

### Week 2

**Unity packages:**

https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@5.1/manual/index.html

MRTK-Unity: https://github.com/microsoft/MixedRealityToolkit-Unity
*MRTK2 eye-tracking only works on HoloLens. MRTK3 works on other devices (e.g.MetaQuest), requires more research on compatibilty of eye-tracking tool kits*

**Related  work on eye-tracking**

[Using Eyetracking to Control my Game](https://www.youtube.com/watch?v=lM8LQVDANfk)

[How To Track Eye Movement In Augmented Reality (Part 1 Face Mesh And BlendShapes)](https://www.youtube.com/watch?v=Zjdw8bHsvXc)

[Unity3d with AR Foundation - How To Setup and Implement AR Eye Tracking?](https://www.youtube.com/watch?v=kIcvAi60qlI)

[MRTK on Oculus Quest 2](https://www.youtube.com/watch?v=YLntpH_tYz4)

[Add Eye Tracking Features With Oculus Integration For Unity](https://www.youtube.com/watch?v=ZoySn7QlMfQ&t=3s)

### Week 3

[VR set up in Unity](https://developer.oculus.com/documentation/unity/unity-conf-settings/#enable-vr-support)

[Oculus Integration SDK](https://developer.oculus.com/documentation/unity/unity-import/#import-sdk-from-unity-asset-store)

[Oculus XR plugin](https://developer.oculus.com/documentation/unity/unity-xr-plugin/)

Task: Follow [the video](https://www.youtube.com/watch?v=ZoySn7QlMfQ&t=3s) and code the app

### Week 4

Cast VR screen to PC using SideQuest [download link](https://sidequestvr.com/download)

Look into decreasing the inconsistent movement of the rays by not moving the ray when eye gaze change is minimal

Turn the ray into dot for better selection

### Week 5

https://github.com/nganphan123/COSC-449/assets/58235340/81fcf745-e827-418c-9552-356e76413190

Oculus eye-gaze api doesn't work well with side eye-gaze. To decrease the offset between the ray and the object, user needs to face directly to the object.

