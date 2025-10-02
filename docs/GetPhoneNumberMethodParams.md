# GetPhoneNumberMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **List[int]** | Array of property IDs | [optional] 
**switch_code** | **str** | This is an optional field. This field accepts single value. | [optional] 
**ref** | **str** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from entrata_api_client.models.get_phone_number_method_params import GetPhoneNumberMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetPhoneNumberMethodParams from a JSON string
get_phone_number_method_params_instance = GetPhoneNumberMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetPhoneNumberMethodParams.to_json())

# convert the object into a dict
get_phone_number_method_params_dict = get_phone_number_method_params_instance.to_dict()
# create an instance of GetPhoneNumberMethodParams from a dict
get_phone_number_method_params_from_dict = GetPhoneNumberMethodParams.from_dict(get_phone_number_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


