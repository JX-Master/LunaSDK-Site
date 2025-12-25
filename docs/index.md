![LOGO](logo.png)

# LunaSDK

LunaSDK is a C++ software development framework for real-time rendering applications like video games, interactive multimedia programs, data visualization programs and so on.

Specifications:

* Self-implemented fundamental libraries, including platform abstraction layer, container library, math library and more. No dependency on C++ STL.
* Full dynamic type reflection, including full support for generic types.
* Serialization and deserialization based on reflection, including JSON and XML support.
* Job system and thread pool for asynchronous computing.
* Render Hardware Interface (RHI) targeting Direct3D 12, Vulkan and Metal.
* Window management API.
* Shader compiling APIs that compile HLSL shaders to DXIL, SPIR-V and Metal.
* Low-latency Audio Hardware Interface (AHI).
* Human Interface Device API providing APIs to access input / output devices.
* Asset system and virtual file system for managing assets at runtime.
* File loader for image files, font files and .OBJ files.
* GPU-driven vector graphics rendering.
* Well documented and CI tested.

Designed target platforms:

* Windows (Direct3D 12+/Vulkan 1.0+)
* macOS (Metal 2+)
* Linux (Vulkan) (Not implemented yet.)
* Android (Vulkan 1.0+)
* iOS (Metal 2+)