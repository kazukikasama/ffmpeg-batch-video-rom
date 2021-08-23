# ffmpeg-batch-video-rom
profile command for ffmpeg batch converter, for rom skraper video
to reduce the size of the video preview files.
`````
-c:v libx265 -crf 18 -c:a mp3 -b:a 128k  -vf scale=320:240,fps=30 -ss 00 -t 25
