# openapi_client.model.lipsync_text_to_templated_video_request.LipsyncTextToTemplatedVideoRequest

Get video where someone says your text. Standart Frontend request.

## Model Type Info
Input Type | Accessed Type | Description | Notes
------------ | ------------- | ------------- | -------------
dict, frozendict.frozendict,  | frozendict.frozendict,  | Get video where someone says your text. Standart Frontend request. | 

### Dictionary Keys
Key | Input Type | Accessed Type | Description | Notes
------------ | ------------- | ------------- | ------------- | -------------
**ID** | str,  | str,  | The identifier of the message. Used for tracking. Random UUID4 if not specified. Don&#x27;t use if you don&#x27;t need it specifically | [optional] 
**token** | str,  | str,  | The token for query. make sure you have correct permissions | [optional] 
**text** | str,  | str,  | Text to say. | [optional] 
**template** | str,  | str,  | Template, f.e. \&quot;santa\&quot;. | [optional] 
**any_string_name** | dict, frozendict.frozendict, str, date, datetime, int, float, bool, decimal.Decimal, None, list, tuple, bytes, io.FileIO, io.BufferedReader | frozendict.frozendict, str, BoolClass, decimal.Decimal, NoneClass, tuple, bytes, FileIO | any string name can be used but the value must be the correct type | [optional]

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

