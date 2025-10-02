# GetPropertyFeesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | This is a required field. This field accepts single value. propertyId | 

## Example

```python
from entrata_api_client.models.get_property_fees_method_params import GetPropertyFeesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyFeesMethodParams from a JSON string
get_property_fees_method_params_instance = GetPropertyFeesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetPropertyFeesMethodParams.to_json())

# convert the object into a dict
get_property_fees_method_params_dict = get_property_fees_method_params_instance.to_dict()
# create an instance of GetPropertyFeesMethodParams from a dict
get_property_fees_method_params_from_dict = GetPropertyFeesMethodParams.from_dict(get_property_fees_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


