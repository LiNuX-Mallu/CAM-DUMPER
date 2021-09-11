<h1 align="center">CAM-DUMPER</h1>
<p align="center"><img src="cd.jpg" max-width="90%%" height="auto"></p>
<p align="center">Take webcam shots from target by just sending a malicious link</p>

# How it works?
<p>The tool generates a malicious HTTPS page using Serveo or Ngrok Port Forwarding methods, and a javascript code to cam requests using MediaDevices.getUserMedia. </p>

<p>The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types. </p>

[See more about MediaDEvices.getUserMedia() here](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)

## Installing (Kali Linux/Termux):


```
$ apt update && apt upgrade
$ apt install git php wget curl jq
$ git clone https://github.com/LiNuX-Mallu/CAM-DUMPER.git
$ cd CAM-DUMPER
$ chmod +x camdumper.sh
$ ./camdumper.sh
```

<p> Termux users should install <a href="https://play.google.com/store/apps/details?id=me.zhanghai.android.files">  MATERIAL FILES  </a> app from playstore for easy managing captured files.</p> 

<b>happy hacking : ]<b>
