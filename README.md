The Mesh Physical Material extension allows you to apply physically accurate materials to meshes using the THREE.js library.

The extension has two actions in the events sheet:
1. Mesh physical material with color
2. Mesh physical material with textures

In these, you can configure a wide range of material parameters, such as roughness, metalness, IOR, reflectivity, and even the reflection type. It can be set to default or dynamic cubemap, allowing you to see true dynamic reflections in real time. These can significantly impact performance, so it’s best to use them sparingly. To bake reflections when the scene starts, set the condition to “At the beginning of the scene” in the material application event. Reflections may apply before the scene is fully rendered, so it’s advisable to add a “Wait X seconds” action before applying the material.
