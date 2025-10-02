# CancelLeaseMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**lease_id** | **int** | This is a required field. This field accepts single value. | 

## Example

```python
from entrata_api_client.models.cancel_lease_method_params import CancelLeaseMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of CancelLeaseMethodParams from a JSON string
cancel_lease_method_params_instance = CancelLeaseMethodParams.from_json(json)
# print the JSON string representation of the object
print(CancelLeaseMethodParams.to_json())

# convert the object into a dict
cancel_lease_method_params_dict = cancel_lease_method_params_instance.to_dict()
# create an instance of CancelLeaseMethodParams from a dict
cancel_lease_method_params_from_dict = CancelLeaseMethodParams.from_dict(cancel_lease_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


