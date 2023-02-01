# openapi_client.model.utils_speech_config.UtilsSpeechConfig

## Model Type Info
Input Type | Accessed Type | Description | Notes
------------ | ------------- | ------------- | -------------
dict, frozendict.frozendict,  | frozendict.frozendict,  |  | 

### Dictionary Keys
Key | Input Type | Accessed Type | Description | Notes
------------ | ------------- | ------------- | ------------- | -------------
**modelId** | str,  | str,  |  | [optional] 
**speed** | decimal.Decimal, int, float,  | decimal.Decimal,  | Speed coefficient. | [optional] value must be a 64 bit float
**expression** | decimal.Decimal, int, float,  | decimal.Decimal,  | Expression coefficient. | [optional] value must be a 64 bit float
**padMsLeft** | decimal.Decimal, int,  | decimal.Decimal,  | Milliseconds of silence appended to the left of result audio. | [optional] value must be a 32 bit integer
**padMsRight** | decimal.Decimal, int,  | decimal.Decimal,  | Milliseconds of silence appended to the right of result audio. | [optional] value must be a 32 bit integer
**any_string_name** | dict, frozendict.frozendict, str, date, datetime, int, float, bool, decimal.Decimal, None, list, tuple, bytes, io.FileIO, io.BufferedReader | frozendict.frozendict, str, BoolClass, decimal.Decimal, NoneClass, tuple, bytes, FileIO | any string name can be used but the value must be the correct type | [optional]

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

