the [images](images) were generated with [FFmpeg](https://github.com/FFmpeg/FFmpeg) with the following command 
```cmd
ffmpeg.exe -i video.mp4 -vf yadif images/%05d.png
```
this should extract frames without interlacing

the [3D Models](texturedMeshes) were generated using default settings with [meshroom](https://github.com/alicevision/meshroom)

this render was done in Blender 

![render](render/render.png)