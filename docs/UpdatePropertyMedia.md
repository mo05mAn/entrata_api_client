# UpdatePropertyMedia


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**UpdatePropertyMediaAuth**](UpdatePropertyMediaAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdatePropertyMediaMethod**](UpdatePropertyMediaMethod.md) |  | 

## Example

```python
from openapi_client.models.update_property_media import UpdatePropertyMedia

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePropertyMedia from a JSON string
update_property_media_instance = UpdatePropertyMedia.from_json(json)
# print the JSON string representation of the object
print(UpdatePropertyMedia.to_json())

# convert the object into a dict
update_property_media_dict = update_property_media_instance.to_dict()
# create an instance of UpdatePropertyMedia from a dict
update_property_media_from_dict = UpdatePropertyMedia.from_dict(update_property_media_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


