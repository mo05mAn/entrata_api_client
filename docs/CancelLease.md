# CancelLease


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**CancelLeaseMethod**](CancelLeaseMethod.md) |  | 

## Example

```python
from openapi_client.models.cancel_lease import CancelLease

# TODO update the JSON string below
json = "{}"
# create an instance of CancelLease from a JSON string
cancel_lease_instance = CancelLease.from_json(json)
# print the JSON string representation of the object
print(CancelLease.to_json())

# convert the object into a dict
cancel_lease_dict = cancel_lease_instance.to_dict()
# create an instance of CancelLease from a dict
cancel_lease_from_dict = CancelLease.from_dict(cancel_lease_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


