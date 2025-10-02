# GetPropertyMediaMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | This is a required field. This field accepts single value. | 
**media_type_id** | **str** | This is a required field. This field accepts single value. | 
**media_sub_type_id** | **str** | This is a required field. This field accepts single value. | 
**reference_ids** | **str** | This is an optional field. This field accepts single value. reference id for mediaType | [optional] 

## Example

```python
from entrata_api_client.models.get_property_media_method_params import GetPropertyMediaMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyMediaMethodParams from a JSON string
get_property_media_method_params_instance = GetPropertyMediaMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetPropertyMediaMethodParams.to_json())

# convert the object into a dict
get_property_media_method_params_dict = get_property_media_method_params_instance.to_dict()
# create an instance of GetPropertyMediaMethodParams from a dict
get_property_media_method_params_from_dict = GetPropertyMediaMethodParams.from_dict(get_property_media_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


