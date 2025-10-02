# GetPropertyPickListsR1SuccessResponseResult

Contains company, property, and search area data

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**company** | [**GetPropertyPickListsR1SuccessResponseResultCompany**](GetPropertyPickListsR1SuccessResponseResultCompany.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_pick_lists_r1_success_response_result import GetPropertyPickListsR1SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyPickListsR1SuccessResponseResult from a JSON string
get_property_pick_lists_r1_success_response_result_instance = GetPropertyPickListsR1SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetPropertyPickListsR1SuccessResponseResult.to_json())

# convert the object into a dict
get_property_pick_lists_r1_success_response_result_dict = get_property_pick_lists_r1_success_response_result_instance.to_dict()
# create an instance of GetPropertyPickListsR1SuccessResponseResult from a dict
get_property_pick_lists_r1_success_response_result_from_dict = GetPropertyPickListsR1SuccessResponseResult.from_dict(get_property_pick_lists_r1_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


