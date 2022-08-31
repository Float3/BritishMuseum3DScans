I extracted frames from the [videos](videos) with [FFmpeg](https://github.com/FFmpeg/FFmpeg) using the following command 
```cmd
ffmpeg.exe -i video.mp4 -vf yadif images/%05d.png
```
this should extract frames without interlacing.

The [3D Models](texturedMeshes) were generated using default settings with [meshroom](https://github.com/alicevision/meshroom).

The render was done in Blender.

![render](render/render.png)
