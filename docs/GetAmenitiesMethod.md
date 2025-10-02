# GetAmenitiesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetAmenitiesMethodParams**](GetAmenitiesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_amenities_method import GetAmenitiesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenitiesMethod from a JSON string
get_amenities_method_instance = GetAmenitiesMethod.from_json(json)
# print the JSON string representation of the object
print(GetAmenitiesMethod.to_json())

# convert the object into a dict
get_amenities_method_dict = get_amenities_method_instance.to_dict()
# create an instance of GetAmenitiesMethod from a dict
get_amenities_method_from_dict = GetAmenitiesMethod.from_dict(get_amenities_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


