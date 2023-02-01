# openapi_client.model.myna_gateway_response.MynaGatewayResponse

## Model Type Info
Input Type | Accessed Type | Description | Notes
------------ | ------------- | ------------- | -------------
dict, frozendict.frozendict,  | frozendict.frozendict,  |  | 

### Dictionary Keys
Key | Input Type | Accessed Type | Description | Notes
------------ | ------------- | ------------- | ------------- | -------------
**ID** | str,  | str,  |  | [optional] 
**statusCode** | [**RpcCode**](RpcCode.md) | [**RpcCode**](RpcCode.md) |  | [optional] 
**errorMessage** | str,  | str,  |  | [optional] 
**tts** | [**TtsTTSResponse**](TtsTTSResponse.md) | [**TtsTTSResponse**](TtsTTSResponse.md) |  | [optional] 
**vc** | [**VcVCResponse**](VcVCResponse.md) | [**VcVCResponse**](VcVCResponse.md) |  | [optional] 
**lipsync** | [**LipsyncLipSyncResponse**](LipsyncLipSyncResponse.md) | [**LipsyncLipSyncResponse**](LipsyncLipSyncResponse.md) |  | [optional] 
**greeting** | [**LipsyncGreetingResponse**](LipsyncGreetingResponse.md) | [**LipsyncGreetingResponse**](LipsyncGreetingResponse.md) |  | [optional] 
**textToTemplatedVideo** | [**LipsyncTextToTemplatedVideoResponse**](LipsyncTextToTemplatedVideoResponse.md) | [**LipsyncTextToTemplatedVideoResponse**](LipsyncTextToTemplatedVideoResponse.md) |  | [optional] 
**customVideo** | [**LipsyncCustomVideoResponse**](LipsyncCustomVideoResponse.md) | [**LipsyncCustomVideoResponse**](LipsyncCustomVideoResponse.md) |  | [optional] 
**newTts** | [**TtsNewTTSResponse**](TtsNewTTSResponse.md) | [**TtsNewTTSResponse**](TtsNewTTSResponse.md) |  | [optional] 
**newVc** | [**VcNewVCResponse**](VcNewVCResponse.md) | [**VcNewVCResponse**](VcNewVCResponse.md) |  | [optional] 
**contentLipsync** | [**LipsyncContentLipSyncResponse**](LipsyncContentLipSyncResponse.md) | [**LipsyncContentLipSyncResponse**](LipsyncContentLipSyncResponse.md) |  | [optional] 
**randomPrediction** | [**DemosRandomPredictionResponse**](DemosRandomPredictionResponse.md) | [**DemosRandomPredictionResponse**](DemosRandomPredictionResponse.md) |  | [optional] 
**audio** | [**UtilsAudio**](UtilsAudio.md) | [**UtilsAudio**](UtilsAudio.md) |  | [optional] 
**text** | str,  | str,  |  | [optional] 
**[empty](#empty)** | dict, frozendict.frozendict,  | frozendict.frozendict,  |  | [optional] 
**any_string_name** | dict, frozendict.frozendict, str, date, datetime, int, float, bool, decimal.Decimal, None, list, tuple, bytes, io.FileIO, io.BufferedReader | frozendict.frozendict, str, BoolClass, decimal.Decimal, NoneClass, tuple, bytes, FileIO | any string name can be used but the value must be the correct type | [optional]

# empty

## Model Type Info
Input Type | Accessed Type | Description | Notes
------------ | ------------- | ------------- | -------------
dict, frozendict.frozendict,  | frozendict.frozendict,  |  | 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

