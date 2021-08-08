# Pytorch_Yolor_DeepSort
 Yolor and  DeepSort
 
<video id="video" controls="" preload="none" poster="封面">
      <source id="mp4" src="result.mp4" type="video/mp4">
</videos>

<video id="video" controls="" preload="none" poster="封面">
      <source id="webm" src="result.webm" type="video/webm">
</videos>

 
 ## Tracking sources

Tracking can be run on most video formats

```bash
python3 track.py --source ... --show-vid  # show live inference results as well
```

- Video:  `--source file.mp4`
- Webcam:  `--source 0`
- RTSP stream:  `--source rtsp://170.93.143.139/rtplive/470011e600ef003a004ee33696235daa`
- HTTP stream:  `--source http://wmccpinetop.axiscam.net/mjpg/video.mjpg`
