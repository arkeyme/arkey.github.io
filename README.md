### Tips & Trics

`.\ffmpeg.exe -ss 00:25:13 -i "Энни Холл (1977. Annie Hall).mkv" -c copy -t 00:01:31 -c:v libx264 -map 0:v:0 -map 0:a:1 -c:a aac "Annie Hall-3.mp4"`

- `-map 0:v:0` to select video stream
- `-map 0:a:1` to select audio stream
- `-c:v libx264` convert to mp4
- `-c:a aac`convert audio to aac codec
