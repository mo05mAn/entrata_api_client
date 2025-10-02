# GetLeaseDetailsR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeaseDetailsR1Method**](GetLeaseDetailsR1Method.md) |  | 

## Example

```python
from openapi_client.models.get_lease_details_r1 import GetLeaseDetailsR1

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1 from a JSON string
get_lease_details_r1_instance = GetLeaseDetailsR1.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1.to_json())

# convert the object into a dict
get_lease_details_r1_dict = get_lease_details_r1_instance.to_dict()
# create an instance of GetLeaseDetailsR1 from a dict
get_lease_details_r1_from_dict = GetLeaseDetailsR1.from_dict(get_lease_details_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


