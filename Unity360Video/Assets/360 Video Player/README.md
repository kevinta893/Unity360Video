# Unity Skybox 360 Video Player

Uses Skybox shader for 360 video:
https://github.com/Unity-Technologies/SkyboxPanoramicShader


360 Video Player in Unity
By: DominiqueLrx
https://forum.unity3d.com/threads/playing-360-videos-with-the-videoplayer.461290/


Sample 360 Videos by: 
https://www.mettle.com/360vr-master-series-free-360-downloads-page/



## How to use
To use, simply use the Main Camera prefab which has the Video Texture for the 360 Skybox made for you.

- See MainCamera/360 Video Player gameobject to change the video being played
- See **Rendering/360VideoRenderTexture.renderTexture** file to change the *resolution* of the video file to be played. This render texture must match the video's resolution.



Troubleshooting:
- If you don't see anything in the windows preview, make sure your graphics card supports the correct DirectX API. Otherwise use only DX9 in the Unity editor
- If you added the Cardboard API, you will not be able to use touch or mouse input like normal. Instead use the cardboard click event or raycasting system in Google Cardboard