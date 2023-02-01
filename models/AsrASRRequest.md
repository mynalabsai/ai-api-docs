# openapi_client.model.asr_asr_request.AsrASRRequest

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
**audio** | [**UtilsAudio**](UtilsAudio.md) | [**UtilsAudio**](UtilsAudio.md) |  | [optional] 
**config** | [**UtilsSpeechConfig**](UtilsSpeechConfig.md) | [**UtilsSpeechConfig**](UtilsSpeechConfig.md) |  | [optional] 
**any_string_name** | dict, frozendict.frozendict, str, date, datetime, int, float, bool, decimal.Decimal, None, list, tuple, bytes, io.FileIO, io.BufferedReader | frozendict.frozendict, str, BoolClass, decimal.Decimal, NoneClass, tuple, bytes, FileIO | any string name can be used but the value must be the correct type | [optional]

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

