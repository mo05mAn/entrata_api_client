# SendPropertyMediaMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | This is a required field. This field accepts single value. The unique identifier for the property. | 
**media** | [**List[MediaItem]**](MediaItem.md) |  | 

## Example

```python
from openapi_client.models.send_property_media_method_params import SendPropertyMediaMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendPropertyMediaMethodParams from a JSON string
send_property_media_method_params_instance = SendPropertyMediaMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendPropertyMediaMethodParams.to_json())

# convert the object into a dict
send_property_media_method_params_dict = send_property_media_method_params_instance.to_dict()
# create an instance of SendPropertyMediaMethodParams from a dict
send_property_media_method_params_from_dict = SendPropertyMediaMethodParams.from_dict(send_property_media_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


