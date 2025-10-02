# GetPropertyFees


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetPropertyFeesMethod**](GetPropertyFeesMethod.md) |  | 

## Example

```python
from openapi_client.models.get_property_fees import GetPropertyFees

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyFees from a JSON string
get_property_fees_instance = GetPropertyFees.from_json(json)
# print the JSON string representation of the object
print(GetPropertyFees.to_json())

# convert the object into a dict
get_property_fees_dict = get_property_fees_instance.to_dict()
# create an instance of GetPropertyFees from a dict
get_property_fees_from_dict = GetPropertyFees.from_dict(get_property_fees_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


