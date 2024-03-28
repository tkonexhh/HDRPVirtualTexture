### API

To access and control this override at runtime, use the [Volume scripting API](../Volumes-API.md#changing-volume-profile-properties). Because of how the Volume system works, you edit properties in a different way to standard Unity components. There are also other nuances to be aware of too, such as each property has an [overrideState](https://docs.unity3d.com/Packages/com.unity.render-pipelines.core@latest/index.html?subfolder=/api/UnityEngine.Rendering.VolumeParameter.html%23UnityEngine_Rendering_VolumeParameter_overrideState). This indicates to the Volume system whether to use the property value you set, or use the default value stored in the [Volume Profile](../create-a-volume-profile.md). For information on how to use the API correctly, see [Volume scripting API](../Volumes-API.md#changing-volume-profile-properties).