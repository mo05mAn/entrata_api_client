# DeletePropertyMedia


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**UpdatePropertyMediaAuth**](UpdatePropertyMediaAuth.md) |  | 
**request_id** | **str** | An arbitrary value to relate with response. | [optional] 
**method** | [**DeletePropertyMediaMethod**](DeletePropertyMediaMethod.md) |  | 

## Example

```python
from openapi_client.models.delete_property_media import DeletePropertyMedia

# TODO update the JSON string below
json = "{}"
# create an instance of DeletePropertyMedia from a JSON string
delete_property_media_instance = DeletePropertyMedia.from_json(json)
# print the JSON string representation of the object
print(DeletePropertyMedia.to_json())

# convert the object into a dict
delete_property_media_dict = delete_property_media_instance.to_dict()
# create an instance of DeletePropertyMedia from a dict
delete_property_media_from_dict = DeletePropertyMedia.from_dict(delete_property_media_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


