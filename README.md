# Sharing Resources Between DirectX and OpenGL

[http://halogenica.net/sharing-resources-between-directx-and-opengl/](http://halogenica.net/sharing-resources-between-directx-and-opengl/)

![Shared Resource Screenshot](https://github.com/halogenica/WGL_NV_DX/blob/master/SharedResource.png)

## Description

This demo illustrates how to use the WGL_NV_DX_Interop extension to efficiently share a resource between DirectX and OpenGL rendering APIs. The intent is to provide common variations of the implementation, as well as a way to enable a performance comparison between CPU and GPU resource copies. 

## Installation

This demo requires the DirectX SDK to be installed, and may require the Windows SDK to be installed as well. 

## Compatibility

Since the time the original article was written, it seems that either the Nvidia driver or modern Nvidia cards, as well as the most recent Intel graphics (Skylake) no longer supports this extension, resulting in failures ranging from black screens to driver crashes. I haven't tested on the most recent AMD cards. I was able to verify that with slightly older Intel hardware (Haswell, HD 4200 - HD 5200) that this extension works across Windows 7, Windows 8.1, and Windows 10. I had previously tested with older AMD hardware (HD 6950) and older Nvidia hardware (GTX 570) which both worked with the texture and offscreen plain methods on Windows 7. 

## License

MIT Licensed, see [LICENSE](https://github.com/halogenica/WGL_NV_DX/blob/master/LICENSE).
