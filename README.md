# 2D-Water-Shader
 2D Water Shader made in HLSL in Unity based on water effect from the game Kingdom!
 
[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X7X223BQX)
 
First off you'll need to create a render texture! Set it's size to some multiple of your screen resolution. For example width can be 1920×3.75=512 and height will then be 1080×3.75=288.

After that create a new camera and as the Target Texture assign previously created render texture. You should now have two cameras in the scene.

For the final step create new 3D plane and create material for it which will be using Custom/WaterShader as its shader.

Variables Description:
* Texture: Your render texture
* Displacement Texture: Your primary displacement texture for the water, you can find example texture in the Textures folder
* Displacement Speed: How fast will your displacement texture scroll
* Displacement Detail Texture: Secondary displacement texture for the water which should add more details to your water, you can find example texture in the Textures folder
* Displacement Detail Speed: How fast will your displacement detail texture scroll
* Displacement Amount Divider: How much effect will your displacement texture have, the lower the value, the more effect it has
* Foam Threshold: Threshold used for displaying foam, the lower the value, the more foam there will be
* Edge Foam Threshold: Threshold used for displaying edge foam, the lower the value, the more edge foam there will be
* Foam Alpha: Alpha color value of the foam
* Parallax Divider: How much parallax effect will there be on camera movement, the lower the value, the more effect it has
* Perspective correction: Do you want your water to be slightly rotated and have correct perspection
* Vertex Displacement: Toggle this if you want to slightly displace your plane
* Vertex Displacement Texture: Texture for your vertex displacement, perlin noise texture can be found in the Textures folder
* Vertex Displacement Amount Divider: How much vertex displacement will there be, the lower the value, the more effect it has
* Vertex Displacement Speed Divider: How frequently should vertex displacement change, the lower the value, the more frequent it is

You are free to use this shader on all of your projects, commercial or non-commercial, you don't have to credit me anywhere, even though that would be nice.

Contact:
* Twitter: https://twitter.com/SJovGD
* Reddit: https://www.reddit.com/user/sjovanovic3107
* Unity Asset Store: https://assetstore.unity.com/publishers/32235
* Itch.io page: https://stefanjo.itch.io/

![Example 01](https://i.imgur.com/trfCSmq.png?1)
