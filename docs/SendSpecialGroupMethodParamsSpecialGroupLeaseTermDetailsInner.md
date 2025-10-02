# SendSpecialGroupMethodParamsSpecialGroupLeaseTermDetailsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_term_id** | **str** | This is a required field. Lease term identifier. | 
**lease_start_window_id** | **str** | This is a required field. Lease start window identifier. | 

## Example

```python
from entrata_api_client.models.send_special_group_method_params_special_group_lease_term_details_inner import SendSpecialGroupMethodParamsSpecialGroupLeaseTermDetailsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendSpecialGroupMethodParamsSpecialGroupLeaseTermDetailsInner from a JSON string
send_special_group_method_params_special_group_lease_term_details_inner_instance = SendSpecialGroupMethodParamsSpecialGroupLeaseTermDetailsInner.from_json(json)
# print the JSON string representation of the object
print(SendSpecialGroupMethodParamsSpecialGroupLeaseTermDetailsInner.to_json())

# convert the object into a dict
send_special_group_method_params_special_group_lease_term_details_inner_dict = send_special_group_method_params_special_group_lease_term_details_inner_instance.to_dict()
# create an instance of SendSpecialGroupMethodParamsSpecialGroupLeaseTermDetailsInner from a dict
send_special_group_method_params_special_group_lease_term_details_inner_from_dict = SendSpecialGroupMethodParamsSpecialGroupLeaseTermDetailsInner.from_dict(send_special_group_method_params_special_group_lease_term_details_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


