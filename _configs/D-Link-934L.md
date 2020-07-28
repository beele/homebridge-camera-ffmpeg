---
title: D-Link 934L
author: Gamer106
date: 2018-09-01
---
Tested on Raspberry Pi 3 (with omx)

## config.json

```json
{
	"name": "D-Link Camera",
	"videoConfig": {
		"source": "-f mjpeg -i http://admin:password@localip:port/video.cgi",
		"stillImageSource": "-f mjpeg -i http://admin:password@localip:port/image/jpeg.cgi",
		"maxStreams": 2,
		"maxWidth": 640,
		"maxHeight": 480,
		"maxFPS": 20
	}
}
```
