# ffmpeg-batch-video-rom
profile command for FFmpeg batch AV converter, for rom skraper video
to reduce the size of the video preview files in mini consoles like Retroid Pocket 2 and others.
`````
-c:v libx264 -crf 18 -c:a aac -b:a 128k  -vf scale=320:240,fps=30 -ss 00 -t 25
