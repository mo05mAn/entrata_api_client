# GetVendorPickListsSuccessResponseResultPoliciesPolicyInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**policy_type_id** | **str** | ID for the policy type. | 
**policy_type_name** | **str** | Name of the policy type. | 
**coverages** | [**GetVendorPickListsSuccessResponseResultPoliciesPolicyInnerCoverages**](GetVendorPickListsSuccessResponseResultPoliciesPolicyInnerCoverages.md) |  | 

## Example

```python
from openapi_client.models.get_vendor_pick_lists_success_response_result_policies_policy_inner import GetVendorPickListsSuccessResponseResultPoliciesPolicyInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorPickListsSuccessResponseResultPoliciesPolicyInner from a JSON string
get_vendor_pick_lists_success_response_result_policies_policy_inner_instance = GetVendorPickListsSuccessResponseResultPoliciesPolicyInner.from_json(json)
# print the JSON string representation of the object
print(GetVendorPickListsSuccessResponseResultPoliciesPolicyInner.to_json())

# convert the object into a dict
get_vendor_pick_lists_success_response_result_policies_policy_inner_dict = get_vendor_pick_lists_success_response_result_policies_policy_inner_instance.to_dict()
# create an instance of GetVendorPickListsSuccessResponseResultPoliciesPolicyInner from a dict
get_vendor_pick_lists_success_response_result_policies_policy_inner_from_dict = GetVendorPickListsSuccessResponseResultPoliciesPolicyInner.from_dict(get_vendor_pick_lists_success_response_result_policies_policy_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


