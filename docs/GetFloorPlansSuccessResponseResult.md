# GetFloorPlansSuccessResponseResult

Result containing floor plan details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**floor_plans** | [**GetFloorPlansSuccessResponseResultFloorPlans**](GetFloorPlansSuccessResponseResultFloorPlans.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_floor_plans_success_response_result import GetFloorPlansSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetFloorPlansSuccessResponseResult from a JSON string
get_floor_plans_success_response_result_instance = GetFloorPlansSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetFloorPlansSuccessResponseResult.to_json())

# convert the object into a dict
get_floor_plans_success_response_result_dict = get_floor_plans_success_response_result_instance.to_dict()
# create an instance of GetFloorPlansSuccessResponseResult from a dict
get_floor_plans_success_response_result_from_dict = GetFloorPlansSuccessResponseResult.from_dict(get_floor_plans_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


