# GetLeaseDetailsR1MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**lease_id** | **int** | This is a required field. This field accepts single value. | 
**include_add_ons** | **int** | This is a required field. This field accepts single value. | [optional] 
**include_charge** | **int** | This is a required field. This field accepts single value. | [optional] 

## Example

```python
from entrata_api_client.models.get_lease_details_r1_method_params import GetLeaseDetailsR1MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1MethodParams from a JSON string
get_lease_details_r1_method_params_instance = GetLeaseDetailsR1MethodParams.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1MethodParams.to_json())

# convert the object into a dict
get_lease_details_r1_method_params_dict = get_lease_details_r1_method_params_instance.to_dict()
# create an instance of GetLeaseDetailsR1MethodParams from a dict
get_lease_details_r1_method_params_from_dict = GetLeaseDetailsR1MethodParams.from_dict(get_lease_details_r1_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


