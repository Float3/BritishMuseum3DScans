I extracted frames from the [videos](videos) with [FFmpeg](https://github.com/FFmpeg/FFmpeg) using the following command 
```cmd
ffmpeg -i video.mp4 -vf yadif images/%05d.png
```

this should extract frames without interlacing.

The [3D Models](texturedMeshes) were generated using default settings with [meshroom](https://github.com/alicevision/meshroom).

The render was done in Blender.

![render](render/render.png)


https://user-images.githubusercontent.com/86748455/187789791-ac29d79c-bbd2-4c5a-9daa-6fdf2aa7ca0c.mp4



https://user-images.githubusercontent.com/86748455/187789859-020f027b-f75d-42bd-8d21-84de496a4a5b.mp4



https://user-images.githubusercontent.com/86748455/187790014-826313b6-6bfb-49c6-8968-7af5b26155cb.mp4



https://user-images.githubusercontent.com/86748455/187790070-c733ba8c-dbd9-46d0-b490-cdeebb3084f3.mp4

