## v1.5.0
-- Adds gameplay-tests project as a test app for various engine features. More tests will be added in the future.
-- Fixes the texture coordinates of Mesh::createQuad(float x, float y, float width, float height).

## v1.4.0

- Lua script bindings for all gameplay interfaces.
- Lua script binding generator tool (gameplay-luagen) for generating gameplay Lua bindings from doxygen xml output.
- AIController, AIAgent, AIStateMachine, AIState and AIMessage clases for scripted AI support.
- Sample for sample05-lua to demonstrate basic Lua with AI scripting.
- Gamepad class with virtual gamepad support.
- Pre-built versions gameplay-encoder added to bin folder with TTF, DAE and FBX support built-in.
- Improved modular shaders with support for #include in shaders. (breaks compat. for shaders)
- LightMap support into colored-unlit.frag and textured-unlit.frag shaders.
- Adds cloning and wireframing features to sample03-character.
- Adds kick the ball on the sample03-character to demonstrate 2 buttons and more physics.
- Fixes missing mouse events on UI controls.
- Fixes to gameplay-encoder to prompt user for font size if not specified.
- Fixes to add "-g" as short form argument for grouping animations.
- Fixes node cloning.
- Fixes to gameplay-encoder for output file path when encoding fonts.
- Fixes to FrameBuffer, RenderTarget and DepthStencilTarget.
- Fixes user switching in MacOSX to other applications with Apple-Tab.
- Fixes measureText with empty string to be proper size.
- Fixed for aliased text by applying linear filtering by default on Fonts.
- Fixes RenderState::StateBlock::bindNoRestore() issue where blend function was not restored to the proper defaults.
- Fixes some inconsistencies in Game event method names for menuEvent. (breaks compat. in Game)
- Fixes some inconsistencies with AnimationClip::getID() to be same as Node::getId() and other classes. (breaks compat. in AnimationClip)
- Fixes to gameplay-encoder and PhysicsRigidBody for heightmaps which adds height precision into generated heightmap png's.

## v1.3.0

- Portrait mode games on mobile platforms.
- Fullscreen and configurable game resolutions on desktop platforms.
- User Interface support for scrolling with scrollbars on Container.
- PVRTC, ATC and DXT texture compression support.
- Performance improvements in user interface forms and text.
- Performance improvements in animations on transforms.
- Performance improvements using NEON math for BlackBerry and iOS.
- Fixes for improvements in error handling throughout all systems.
- Fixes supporting built-in Maya COLLADA exporter via DAE_FBX export.
- Fixes for latest FBX SDK 2013 support.
- Fixes for loading from some WAV files that were crashing.
- Fixes for From/By animations.
- Fixes allowing all inline properties loaded within .scene files. (breaks compat. for .scene)
- Fixes in .scene files for collisionObject definitions (breaks compat. for .scene)
- Fixes for depth/z-ordering of controls.

## v1.2.0

- BlackBerry 10 support.
- iOS 5.1 support.
- Android 2.3+ support.
- User interface system with declaritive forms and themes.
- Bluetooth keyboard/mouse support on BlackBerry platform.
- Developer guide.
- Sample/turorial for sample03-character.
- Sample for sample04-particles to demonstrate particle emitters.
- Fixes for loading properties from URL.
- Fixes on Win32/MacOSX for when mouse pointer leaves the window and returns.
- Fixes to accelerometer for Android.
- Fixes in animation blending.
- Fixes to GPB for loading from single node and parent node. (breaks compat. for .gpb)

## v1.1.0

- FBX support in gameplay-encoder.
- MacOSX platform support using XCode.
- Offscreen rendering functionality using FrameBuffer.
- Loading 3D scences using declaritive .scene files.
- Loading audio from .ogg files using vorbis.
- Loading AudioSources from .audio files.
- Loading Animations from .animation files.
- AnimationClip support for cross fading.
- Physics support using Bullet Physics.
- Cross-platform new project generator.
- Overloaded operators in Math classes.
- Font improvements for justify, clip, wrap and scaling.
- Fixes for Font::drawText to use point size and not float scalar.
- Fixes for memory leaks in and fixes to AnimationTarget.
- Fixes for bumped and paralax shaders.
- Fixes to simplify folders for resources in samples.
- Fixes to the material/shader system.
- Fixes to the ParticleEmitter.

## v1.0.1

- Initial release.




