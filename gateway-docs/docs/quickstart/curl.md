# Curl

TLDR: запрашиваем tts

```
curl https://gateway.mynaservice.ai/v1/tts -X POST -H "Content-Type: application/json" -d '{"ID": "test-tts",  "token": "ZXlKMGVYQWlPaUpLVjFRaUxDSmhiR2NpT2lKSVV6STFOaUo5LmV5SjBkSE1pT25zaWJtOXNhVzFwZENJNmRISjFaWDE5LjJBREdPeS1CUTlMbWZSMWE3RXpfNEhpT2NIUkRGNWF6X3JVRi1wMmY0MzQ=","text": "i am the president of the united states","speaker": "obama","speed": 1.0,"padMsLeft": 0,"padMsRight": 0}'
```

```jsx
{
	"ID": "test-tts",
	"token": "ZXlKMGVYQWlPaUpLVjFRaUxDSmhiR2NpT2lKSVV6STFOaUo5LmV5SjBkSE1pT25zaWJtOXNhVzFwZENJNmRISjFaWDE5LjJBREdPeS1CUTlMbWZSMWE3RXpfNEhpT2NIUkRGNWF6X3JVRi1wMmY0MzQ=", 
	"text": "i am the president of the united states",
	"speaker": "obama",
	"speed": 1.0,
  "padMsLeft": 0,
  "padMsRight": 0,
}
```

`token` — тестовый токен, подробнее смотри [Auth / token](./auth) 

`ID` — id запроса, используется для трейсинга, логирования и прочего. Лучше не задавать, тогда это будет случайный UUID

`text`, `speaker`, `speed`, `padMsLeft`, `padMsRight` — параметры ттс

you can find test requests here [https://github.com/mynalabsai/gateway/tree/master/json](https://github.com/mynalabsai/gateway/tree/master/json)