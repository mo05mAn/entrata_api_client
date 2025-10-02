# GetLeaseDetailsR1Method


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetLeaseDetailsR1MethodParams**](GetLeaseDetailsR1MethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_lease_details_r1_method import GetLeaseDetailsR1Method

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1Method from a JSON string
get_lease_details_r1_method_instance = GetLeaseDetailsR1Method.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1Method.to_json())

# convert the object into a dict
get_lease_details_r1_method_dict = get_lease_details_r1_method_instance.to_dict()
# create an instance of GetLeaseDetailsR1Method from a dict
get_lease_details_r1_method_from_dict = GetLeaseDetailsR1Method.from_dict(get_lease_details_r1_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


