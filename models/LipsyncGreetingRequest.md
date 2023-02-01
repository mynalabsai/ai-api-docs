# openapi_client.model.lipsync_greeting_request.LipsyncGreetingRequest

Greeting request. Get Id for template, for voice and send name.

## Model Type Info
Input Type | Accessed Type | Description | Notes
------------ | ------------- | ------------- | -------------
dict, frozendict.frozendict,  | frozendict.frozendict,  | Greeting request. Get Id for template, for voice and send name. | 

### Dictionary Keys
Key | Input Type | Accessed Type | Description | Notes
------------ | ------------- | ------------- | ------------- | -------------
**ID** | str,  | str,  | The identifier of the message. Used for tracking. Random UUID4 if not specified. Don&#x27;t use if you don&#x27;t need it specifically | [optional] 
**token** | str,  | str,  | The token for query. make sure you have correct permissions | [optional] 
**templateId** | str,  | str,  | The identifier of template. | [optional] 
**voiceId** | str,  | str,  | The identifier of voice. | [optional] 
**name** | str,  | str,  | Name to greet. | [optional] 
**any_string_name** | dict, frozendict.frozendict, str, date, datetime, int, float, bool, decimal.Decimal, None, list, tuple, bytes, io.FileIO, io.BufferedReader | frozendict.frozendict, str, BoolClass, decimal.Decimal, NoneClass, tuple, bytes, FileIO | any string name can be used but the value must be the correct type | [optional]

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

