# TTS

```
curl https://gateway.mynaservice.ai/v3/tts -X POST -H "Content-Type: application/json" -d '{"ID": "test-tts",  "token": "ZXlKMGVYQWlPaUpLVjFRaUxDSmhiR2NpT2lKSVV6STFOaUo5LmV5SjBkSE1pT25zaWJtOXNhVzFwZENJNmRISjFaWDE5LjJBREdPeS1CUTlMbWZSMWE3RXpfNEhpT2NIUkRGNWF6X3JVRi1wMmY0MzQ=","text": "i am the president of the united states","speaker": {"name": "obama"}}'
```

```jsx
{
	"ID": "test-tts",
	"token": "ZXlKMGVYQWlPaUpLVjFRaUxDSmhiR2NpT2lKSVV6STFOaUo5LmV5SjBkSE1pT25zaWJtOXNhVzFwZENJNmRISjFaWDE5LjJBREdPeS1CUTlMbWZSMWE3RXpfNEhpT2NIUkRGNWF6X3JVRi1wMmY0MzQ=", 
	"text": "i am the president of the united states",
	"speaker": {
		"name": "obama"
	}
}
```

`token` — Test token, read [Auth / token](./auth) for further information.

`ID` — Request ID, which is used for tracing and logging. By default it is a random UUID4 and we believe you should go with default way until you specifically want otherwise

You can find test requests here [https://github.com/mynalabsai/gateway/tree/master/json](https://github.com/mynalabsai/gateway/tree/master/json)