# VC

```
curl https://gateway.mynaservice.ai/v3/vc -X POST -H "Content-Type: multipart/form-data" -F 'data={"ID": "test-vc",  "token": "ZXlKMGVYQWlPaUpLVjFRaUxDSmhiR2NpT2lKSVV6STFOaUo5LmV5SjBkSE1pT25zaWJtOXNhVzFwZENJNmRISjFaWDE5LjJBREdPeS1CUTlMbWZSMWE3RXpfNEhpT2NIUkRGNWF6X3JVRi1wMmY0MzQ=","audio": {"format": "BYTES", "data": "$rickroll"}, "speaker": {"name": "obama"}}' -F 'rickroll=nevergonnagiveyouup.wav'
```

```jsx
{
	"ID": "test-vc",
	"token": "ZXlKMGVYQWlPaUpLVjFRaUxDSmhiR2NpT2lKSVV6STFOaUo5LmV5SjBkSE1pT25zaWJtOXNhVzFwZENJNmRISjFaWDE5LjJBREdPeS1CUTlMbWZSMWE3RXpfNEhpT2NIUkRGNWF6X3JVRi1wMmY0MzQ=", 
	"audio": {
		"format": "BYTES",
		"data": "$rickroll"
	},
	"speaker": {
		"name": "obama"
	}
}
```

`token` — Test token, read [Auth / token](./auth) for further information.

`ID` — Request ID, which is used for tracing and logging. By default it is a random UUID4 and we believe you should go with default way until you specifically want otherwise

There are more ways to upload audio (files, url, raw bytes), have a look [here](../guides/audio.md)