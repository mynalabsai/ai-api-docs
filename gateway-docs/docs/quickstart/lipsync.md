# LipSync

```
curl https://gateway.mynaservice.ai/v1/content-lipsync -X POST -H "Content-Type: multipart/form-data" -F 'data={"ID": "test-lipsync",  "token": "ZXlKMGVYQWlPaUpLVjFRaUxDSmhiR2NpT2lKSVV6STFOaUo5LmV5SjBkSE1pT25zaWJtOXNhVzFwZENJNmRISjFaWDE5LjJBREdPeS1CUTlMbWZSMWE3RXpfNEhpT2NIUkRGNWF6X3JVRi1wMmY0MzQ=","audio": {"format": "BYTES", "data": "$rickroll"}, "video": {"format": "url", "url": "https://www.youtube.com/watch?v=dQw4w9WgXcQ"}}' -F 'rickroll=nevergonnagiveyouup.wav'
```

```jsx
{
	"ID": "test-lipsync",
	"token": "ZXlKMGVYQWlPaUpLVjFRaUxDSmhiR2NpT2lKSVV6STFOaUo5LmV5SjBkSE1pT25zaWJtOXNhVzFwZENJNmRISjFaWDE5LjJBREdPeS1CUTlMbWZSMWE3RXpfNEhpT2NIUkRGNWF6X3JVRi1wMmY0MzQ=", 
	"audio": {
		"format": "BYTES",
		"data": "$rickroll"
	},
	"video": {
		"format": "URL",
		"url": "https://www.youtube.com/watch?v=dQw4w9WgXcQ"	
	}
}
```

`token` — Test token, read [Auth / token](./auth) for further information.

`ID` — Request ID, which is used for tracing and logging. By default it is a random UUID4 and we believe you should go with default way until you specifically want otherwise

There are more ways to upload audio and video (files, url, raw bytes), have a look [here](../guides/audio.md) and [here](../guides/video.md)