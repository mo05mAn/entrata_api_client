# SendFloorplansSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**floorplans** | [**SendFloorplansSuccessResponseResultFloorplans**](SendFloorplansSuccessResponseResultFloorplans.md) |  | 

## Example

```python
from entrata_api_client.models.send_floorplans_success_response_result import SendFloorplansSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendFloorplansSuccessResponseResult from a JSON string
send_floorplans_success_response_result_instance = SendFloorplansSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendFloorplansSuccessResponseResult.to_json())

# convert the object into a dict
send_floorplans_success_response_result_dict = send_floorplans_success_response_result_instance.to_dict()
# create an instance of SendFloorplansSuccessResponseResult from a dict
send_floorplans_success_response_result_from_dict = SendFloorplansSuccessResponseResult.from_dict(send_floorplans_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


