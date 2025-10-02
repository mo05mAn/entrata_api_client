# UpdateLeaseMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**UpdateLeaseMethodParams**](UpdateLeaseMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.update_lease_method import UpdateLeaseMethod

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeaseMethod from a JSON string
update_lease_method_instance = UpdateLeaseMethod.from_json(json)
# print the JSON string representation of the object
print(UpdateLeaseMethod.to_json())

# convert the object into a dict
update_lease_method_dict = update_lease_method_instance.to_dict()
# create an instance of UpdateLeaseMethod from a dict
update_lease_method_from_dict = UpdateLeaseMethod.from_dict(update_lease_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


