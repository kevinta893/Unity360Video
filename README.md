# Unity Skybox 360 Video Player
A very basic 360 video implementation and demo. Uses a SkyBox rendering technique.

Uses the [Skybox Panoramic shader](https://github.com/Unity-Technologies/SkyboxPanoramicShader) by Unity-Technologies

360 Video Player in Unity
By: DominiqueLrx
https://forum.unity3d.com/threads/playing-360-videos-with-the-videoplayer.461290/

Sample 360 Videos by: 
https://www.mettle.com/360vr-master-series-free-360-downloads-page/



How to use:
- See *MainCamera/360 Video Player* gameobject to change the video being played
- See **Rendering/360VideoRenderTexture.renderTexture** file to change the *resolution* of the video file to be played. This render texture must match the video's resolution.



Troubleshooting:
- If you don't see anything in the windows preview, make sure your graphics card supports the correct DirectX API. Otherwise use only DX9 in the Unity editor
