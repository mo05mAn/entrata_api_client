# SuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | an arbitary value sent with the request. | [optional] 
**code** | **int** | Successful response code. | 
**result** | **object** | webservice response data | 

## Example

```python
from openapi_client.models.success_response_response import SuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SuccessResponseResponse from a JSON string
success_response_response_instance = SuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SuccessResponseResponse.to_json())

# convert the object into a dict
success_response_response_dict = success_response_response_instance.to_dict()
# create an instance of SuccessResponseResponse from a dict
success_response_response_from_dict = SuccessResponseResponse.from_dict(success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


