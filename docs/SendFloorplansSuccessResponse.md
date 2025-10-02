# SendFloorplansSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**result** | [**SendFloorplansSuccessResponseResult**](SendFloorplansSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_floorplans_success_response import SendFloorplansSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendFloorplansSuccessResponse from a JSON string
send_floorplans_success_response_instance = SendFloorplansSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendFloorplansSuccessResponse.to_json())

# convert the object into a dict
send_floorplans_success_response_dict = send_floorplans_success_response_instance.to_dict()
# create an instance of SendFloorplansSuccessResponse from a dict
send_floorplans_success_response_from_dict = SendFloorplansSuccessResponse.from_dict(send_floorplans_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


