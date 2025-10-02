# GetLeasePickListSuccessResponseResultChargeCodeTypesChargeCodeTypeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique identifier for the charge code type. | 
**name** | **str** | Name of the charge code type. | 
**allowed_charge_timing_ids** | **str** | Allowed charge timing IDs for this charge code type. | 

## Example

```python
from openapi_client.models.get_lease_pick_list_success_response_result_charge_code_types_charge_code_type_inner import GetLeasePickListSuccessResponseResultChargeCodeTypesChargeCodeTypeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasePickListSuccessResponseResultChargeCodeTypesChargeCodeTypeInner from a JSON string
get_lease_pick_list_success_response_result_charge_code_types_charge_code_type_inner_instance = GetLeasePickListSuccessResponseResultChargeCodeTypesChargeCodeTypeInner.from_json(json)
# print the JSON string representation of the object
print(GetLeasePickListSuccessResponseResultChargeCodeTypesChargeCodeTypeInner.to_json())

# convert the object into a dict
get_lease_pick_list_success_response_result_charge_code_types_charge_code_type_inner_dict = get_lease_pick_list_success_response_result_charge_code_types_charge_code_type_inner_instance.to_dict()
# create an instance of GetLeasePickListSuccessResponseResultChargeCodeTypesChargeCodeTypeInner from a dict
get_lease_pick_list_success_response_result_charge_code_types_charge_code_type_inner_from_dict = GetLeasePickListSuccessResponseResultChargeCodeTypesChargeCodeTypeInner.from_dict(get_lease_pick_list_success_response_result_charge_code_types_charge_code_type_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


