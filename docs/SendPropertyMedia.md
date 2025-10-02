# SendPropertyMedia


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendPropertyMediaMethod**](SendPropertyMediaMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_property_media import SendPropertyMedia

# TODO update the JSON string below
json = "{}"
# create an instance of SendPropertyMedia from a JSON string
send_property_media_instance = SendPropertyMedia.from_json(json)
# print the JSON string representation of the object
print(SendPropertyMedia.to_json())

# convert the object into a dict
send_property_media_dict = send_property_media_instance.to_dict()
# create an instance of SendPropertyMedia from a dict
send_property_media_from_dict = SendPropertyMedia.from_dict(send_property_media_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


