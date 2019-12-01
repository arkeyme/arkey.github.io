### Tips & Trics

`ffmpeg -ss 00:25:13 -i "Input.mkv" -c copy -t 00:01:31 -c:v libx264 -map 0:v:0 -map 0:a:1 -c:a aac "Output.mp4"`

- `-map 0:v:0` to select video stream
- `-map 0:a:1` to select audio stream
- `-c:v libx264` convert to mp4
- `-c:a aac`convert audio to aac codec
