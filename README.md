# COSC-449

Honours thesis regarding eye-tracking applications:

1. Desktop-based application with Tobii device

2. AR application on MetaQuest headset

[Source code](https://github.com/nganphan123/SimpleEyeTracking) 

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

### Week 6

Read abstraction from research paper

|Title                                                                                                          |DOI                            |Keywords                                                                                                    |Source                                                           |
|---------------------------------------------------------------------------------------------------------------|-------------------------------|--------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|
|Prospective on Eye-Tracking-based Studies in Immersive Virtual Reality                                         |10.1109/CSCWD49262.2021.9437692|tracking gaze points to manipulate the VR environment                                                   |https://ieeexplore.ieee.org/abstract/document/9437692            |
|A comparative study of eye tracking and hand controller for aiming tasks in virtual reality                    |10.1145/3317956.3318153        |gaze aiming compared to controller in "aim and shoot" task; qualitative data was gathered               |https://dl.acm.org/doi/abs/10.1145/3317956.3318153               |
|A Fitt's Law Study of Gaze-Hand Alignment for Selection in 3D User Interfaces                                |10.1145/3544548.3581423        |gaze for target pre-selection; Gaze&Finger and Gaze&Handray techniques                                  |https://dl.acm.org/doi/abs/10.1145/3544548.3581423               |
|Comparison of Eye-Based and Controller-Based Selection in Virtual Reality                                      |10.1080/10447318.2020.1826190  |Fitt's modeling of the eye-based selection                                                            |https://www.tandfonline.com/doi/abs/10.1080/10447318.2020.1826190|
|Pinch, Click, or Dwell: Comparing Different Selection Techniques for Eye-Gaze-Based Pointing in Virtual Reality|10.1145/3448018.3457998        |subjects pointed with (eye-)gaze; selected / activated the targets by pinch, clicking a button, or dwell|https://dl.acm.org/doi/abs/10.1145/3448018.3457998               |
|Evaluating ray casting and two gaze-based pointing techniques for object selection in virtual reality          |10.1145/3281505.3283382        |interaction techniques: ray casting, dwell time and gaze trigger in a simple object selection task      |https://dl.acm.org/doi/abs/10.1145/3281505.3283382               |
|Eye&Head: Synergetic Eye and Head Movement for Gaze Pointing and Selection                                     |10.1145/3332165.3347921        |                                                                                                        |https://dl.acm.org/doi/abs/10.1145/3332165.3347921               |

[Similar eye gaze project](https://github.com/fabio914/EyeTrackingKeyboard/blob/main/EyeTrackingKeyboard/Assets/Scripts/EyeTrackingKeyboard.cs)
