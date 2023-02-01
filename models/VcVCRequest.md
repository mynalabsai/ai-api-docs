# openapi_client.model.vc_vc_request.VcVCRequest

VC request. Send speaker id (obama, eilish, etc) and audio bytes. Bytes should be in WAV, raw for GRPC, base64 for HTTP

## Model Type Info
Input Type | Accessed Type | Description | Notes
------------ | ------------- | ------------- | -------------
dict, frozendict.frozendict,  | frozendict.frozendict,  | VC request. Send speaker id (obama, eilish, etc) and audio bytes. Bytes should be in WAV, raw for GRPC, base64 for HTTP | 

### Dictionary Keys
Key | Input Type | Accessed Type | Description | Notes
------------ | ------------- | ------------- | ------------- | -------------
**ID** | str,  | str,  | The identifier of the message. Used for tracking. Random UUID4 if not specified. Don&#x27;t use if you don&#x27;t need it specifically | [optional] 
**token** | str,  | str,  | The token for query. make sure you have correct permissions | [optional] 
**audio** | str,  | str,  | Audio to convert, WAV format. | [optional] 
**speaker** | str,  | str,  | Identifier of speaker. Obama, musk, etc. look at https://tts.mynalabs.ai/ for speakers | [optional] 
**modelId** | str,  | str,  | Identifier of model to use. Only for new vc | [optional] 
**speakerId** | decimal.Decimal, int,  | decimal.Decimal,  | Identifier of speaker. Obama, musk, etc. look at https://tts.mynalabs.ai/ for speakers | [optional] value must be a 32 bit integer
**speed** | decimal.Decimal, int, float,  | decimal.Decimal,  | Speed coefficient. | [optional] value must be a 64 bit float
**expression** | decimal.Decimal, int, float,  | decimal.Decimal,  | Expression coefficient. | [optional] value must be a 64 bit float
**padMsLeft** | decimal.Decimal, int,  | decimal.Decimal,  | Milliseconds of silence appended to the left of result audio. | [optional] value must be a 32 bit integer
**padMsRight** | decimal.Decimal, int,  | decimal.Decimal,  | Milliseconds of silence appended to the right of result audio. | [optional] value must be a 32 bit integer
**any_string_name** | dict, frozendict.frozendict, str, date, datetime, int, float, bool, decimal.Decimal, None, list, tuple, bytes, io.FileIO, io.BufferedReader | frozendict.frozendict, str, BoolClass, decimal.Decimal, NoneClass, tuple, bytes, FileIO | any string name can be used but the value must be the correct type | [optional]

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

