# Unity Generic OpenXR Loader For Android

[![npm version](https://badge.fury.io/js/com.nfynt.openxr.genericandroidloader.svg)](https://badge.fury.io/js/com.nfynt.openxr.genericandroidloader)


A generic [OpenXR loader](https://www.khronos.org/registry/OpenXR/specs/1.0/loader.html) for android devices in Unity. Unity's [OpenXR package](https://docs.unity3d.com/Packages/com.unity.xr.openxr@1.4/manual/index.html) doesn't support runtime discovery on Android as per the [OpenXR specification](https://www.khronos.org/registry/OpenXR/specs/1.0/loader.html#runtime-interaction), and expects XR loader from the respective platform provider (Oculus support feature for default case).

This loader is a simple Unity XR wrapper above Khronos [hello_xr](https://github.com/KhronosGroup/OpenXR-SDK-Source/tree/main/src/tests/hello_xr) loader. It has been tested with Monado Runtime for android with Vulkan and OpenGLES3.

### Importing in Unity

To install this package in Unity you'll first have to add a new Scoped Registry. Head over to `Edit>Project Settings>Package Manager` and add the new registry details as follows - 
```
Name: npmjs
URL: https://registry.npmjs.org
Scope(s): com.nfynt
```

After this head to `Window>Package Manager` and select `My Registries` under the `Packages:` options. This will list all the available package on npm, find `Generic OpenXR Loader` and select the latest version available and hit install 🚀.

### Issues
Submit issues on [Github Repo](https://github.com/nfynt/AndroidOpenXRLoader/issues) with appropriate label as `bug\enhancement\help wanted`.

### Authors
```
Shubham
```
