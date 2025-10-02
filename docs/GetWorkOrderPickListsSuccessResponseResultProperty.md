# GetWorkOrderPickListsSuccessResponseResultProperty


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**locations** | [**GetWorkOrderPickListsSuccessResponseResultPropertyLocations**](GetWorkOrderPickListsSuccessResponseResultPropertyLocations.md) |  | 
**priorities** | [**GetWorkOrderPickListsSuccessResponseResultPropertyPriorities**](GetWorkOrderPickListsSuccessResponseResultPropertyPriorities.md) |  | 
**status_types** | [**GetWorkOrderPickListsSuccessResponseResultPropertyStatusTypes**](GetWorkOrderPickListsSuccessResponseResultPropertyStatusTypes.md) |  | 
**categories** | [**GetWorkOrderPickListsSuccessResponseResultPropertyCategories**](GetWorkOrderPickListsSuccessResponseResultPropertyCategories.md) |  | 
**problems** | [**GetWorkOrderPickListsSuccessResponseResultPropertyProblems**](GetWorkOrderPickListsSuccessResponseResultPropertyProblems.md) |  | 

## Example

```python
from openapi_client.models.get_work_order_pick_lists_success_response_result_property import GetWorkOrderPickListsSuccessResponseResultProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrderPickListsSuccessResponseResultProperty from a JSON string
get_work_order_pick_lists_success_response_result_property_instance = GetWorkOrderPickListsSuccessResponseResultProperty.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrderPickListsSuccessResponseResultProperty.to_json())

# convert the object into a dict
get_work_order_pick_lists_success_response_result_property_dict = get_work_order_pick_lists_success_response_result_property_instance.to_dict()
# create an instance of GetWorkOrderPickListsSuccessResponseResultProperty from a dict
get_work_order_pick_lists_success_response_result_property_from_dict = GetWorkOrderPickListsSuccessResponseResultProperty.from_dict(get_work_order_pick_lists_success_response_result_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


