# UpdatePropertyMediaMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | This is a required field. This field accepts single value. The unique identifier for the property. | 
**media** | [**List[MediaItem]**](MediaItem.md) |  | 

## Example

```python
from entrata_api_client.models.update_property_media_method_params import UpdatePropertyMediaMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePropertyMediaMethodParams from a JSON string
update_property_media_method_params_instance = UpdatePropertyMediaMethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdatePropertyMediaMethodParams.to_json())

# convert the object into a dict
update_property_media_method_params_dict = update_property_media_method_params_instance.to_dict()
# create an instance of UpdatePropertyMediaMethodParams from a dict
update_property_media_method_params_from_dict = UpdatePropertyMediaMethodParams.from_dict(update_property_media_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


