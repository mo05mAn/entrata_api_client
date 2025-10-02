# DeletePropertyMediaMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | Required. The unique identifier for the property. | 
**id** | **str** | Required. The unique identifier for the media. | 

## Example

```python
from openapi_client.models.delete_property_media_method_params import DeletePropertyMediaMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of DeletePropertyMediaMethodParams from a JSON string
delete_property_media_method_params_instance = DeletePropertyMediaMethodParams.from_json(json)
# print the JSON string representation of the object
print(DeletePropertyMediaMethodParams.to_json())

# convert the object into a dict
delete_property_media_method_params_dict = delete_property_media_method_params_instance.to_dict()
# create an instance of DeletePropertyMediaMethodParams from a dict
delete_property_media_method_params_from_dict = DeletePropertyMediaMethodParams.from_dict(delete_property_media_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


