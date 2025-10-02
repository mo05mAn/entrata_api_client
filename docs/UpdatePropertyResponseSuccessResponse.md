# UpdatePropertyResponseSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **int** | The response code indicating the status of the request. | 
**result** | [**UpdatePropertyResponseSuccessResponseResult**](UpdatePropertyResponseSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.update_property_response_success_response import UpdatePropertyResponseSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePropertyResponseSuccessResponse from a JSON string
update_property_response_success_response_instance = UpdatePropertyResponseSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(UpdatePropertyResponseSuccessResponse.to_json())

# convert the object into a dict
update_property_response_success_response_dict = update_property_response_success_response_instance.to_dict()
# create an instance of UpdatePropertyResponseSuccessResponse from a dict
update_property_response_success_response_from_dict = UpdatePropertyResponseSuccessResponse.from_dict(update_property_response_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


