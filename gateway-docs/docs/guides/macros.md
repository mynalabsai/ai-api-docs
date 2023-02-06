# File Macros For REST

There are cases when request contains audio and/or video. By default, if you want to send a custom file in REST, by default you are suppored to send data as bsae64 string in json. It may be okay if request is automatically generated, but it is very inconvinient for manual testing. Json with query can grow in size, you need to manually convert your .WAV to base64, et cetera.

Because of grpc/rest compatibility with grpc-gateway, it is still required to pass bytes as base64 string. Our solution to this problem is preprocessing rest query with `multipart/form-data` content.

You can set macros in format `$MACROS_NAME`, that will substitute json fields with content of a file

Look at this example:

```
{
    "token": "",
    "audio": {
        "data": "$emusk"
    }
}
```

This will expand `data` with `$emusk` file from  multipart/form-data query

Example curl format:

```bash
curl gateway.dev.neiro.ai/v1/asr -X POST 
				-F 'data=@json/asr.json' -F '$emusk=@emusk.wav'
```