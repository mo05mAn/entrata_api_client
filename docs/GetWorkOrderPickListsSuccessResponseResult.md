# GetWorkOrderPickListsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**var_property** | [**GetWorkOrderPickListsSuccessResponseResultProperty**](GetWorkOrderPickListsSuccessResponseResultProperty.md) |  | 
**inspection_statuses** | [**GetWorkOrderPickListsSuccessResponseResultInspectionStatuses**](GetWorkOrderPickListsSuccessResponseResultInspectionStatuses.md) |  | 
**work_order_types** | [**GetWorkOrderPickListsSuccessResponseResultWorkOrderTypes**](GetWorkOrderPickListsSuccessResponseResultWorkOrderTypes.md) |  | 
**company_employees** | [**GetWorkOrderPickListsSuccessResponseResultCompanyEmployees**](GetWorkOrderPickListsSuccessResponseResultCompanyEmployees.md) |  | 

## Example

```python
from entrata_api_client.models.get_work_order_pick_lists_success_response_result import GetWorkOrderPickListsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrderPickListsSuccessResponseResult from a JSON string
get_work_order_pick_lists_success_response_result_instance = GetWorkOrderPickListsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrderPickListsSuccessResponseResult.to_json())

# convert the object into a dict
get_work_order_pick_lists_success_response_result_dict = get_work_order_pick_lists_success_response_result_instance.to_dict()
# create an instance of GetWorkOrderPickListsSuccessResponseResult from a dict
get_work_order_pick_lists_success_response_result_from_dict = GetWorkOrderPickListsSuccessResponseResult.from_dict(get_work_order_pick_lists_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


