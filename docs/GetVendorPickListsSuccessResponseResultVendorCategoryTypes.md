# GetVendorPickListsSuccessResponseResultVendorCategoryTypes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendor_category_type** | [**List[GetVendorPickListsSuccessResponseResultVendorCategoryTypesVendorCategoryTypeInner]**](GetVendorPickListsSuccessResponseResultVendorCategoryTypesVendorCategoryTypeInner.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_vendor_pick_lists_success_response_result_vendor_category_types import GetVendorPickListsSuccessResponseResultVendorCategoryTypes

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorPickListsSuccessResponseResultVendorCategoryTypes from a JSON string
get_vendor_pick_lists_success_response_result_vendor_category_types_instance = GetVendorPickListsSuccessResponseResultVendorCategoryTypes.from_json(json)
# print the JSON string representation of the object
print(GetVendorPickListsSuccessResponseResultVendorCategoryTypes.to_json())

# convert the object into a dict
get_vendor_pick_lists_success_response_result_vendor_category_types_dict = get_vendor_pick_lists_success_response_result_vendor_category_types_instance.to_dict()
# create an instance of GetVendorPickListsSuccessResponseResultVendorCategoryTypes from a dict
get_vendor_pick_lists_success_response_result_vendor_category_types_from_dict = GetVendorPickListsSuccessResponseResultVendorCategoryTypes.from_dict(get_vendor_pick_lists_success_response_result_vendor_category_types_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


