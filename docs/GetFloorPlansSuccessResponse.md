# GetFloorPlansSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**result** | [**GetFloorPlansSuccessResponseResult**](GetFloorPlansSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_floor_plans_success_response import GetFloorPlansSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetFloorPlansSuccessResponse from a JSON string
get_floor_plans_success_response_instance = GetFloorPlansSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetFloorPlansSuccessResponse.to_json())

# convert the object into a dict
get_floor_plans_success_response_dict = get_floor_plans_success_response_instance.to_dict()
# create an instance of GetFloorPlansSuccessResponse from a dict
get_floor_plans_success_response_from_dict = GetFloorPlansSuccessResponse.from_dict(get_floor_plans_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


