# GenerateQuotesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | The response code indicating the result. | 
**result** | [**GenerateQuotesSuccessResponseResult**](GenerateQuotesSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.generate_quotes_success_response import GenerateQuotesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GenerateQuotesSuccessResponse from a JSON string
generate_quotes_success_response_instance = GenerateQuotesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GenerateQuotesSuccessResponse.to_json())

# convert the object into a dict
generate_quotes_success_response_dict = generate_quotes_success_response_instance.to_dict()
# create an instance of GenerateQuotesSuccessResponse from a dict
generate_quotes_success_response_from_dict = GenerateQuotesSuccessResponse.from_dict(generate_quotes_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


