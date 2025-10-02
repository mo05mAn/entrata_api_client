# MediaItem


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the media | 
**media_type_id** | **str** | Type identifier for the media | 
**media_type_name** | **str** | Name of the media type | 
**media_sub_type_id** | **str** | Sub-type identifier for the media | 
**media_sub_type_name** | **str** | Name of the media sub-type | 
**reference_id** | **str** | Reference identifier | 
**media_provider** | **str** | Provider of the media | 
**media_url** | **str** | URL of the media | 
**media_alt_text** | **str** | Alternative text for the media | [optional] 
**name** | **str** | Name of the media | [optional] 
**description** | **str** | Description of the media | [optional] 
**caption** | **str** | Caption for the media | [optional] 
**height** | **str** | Height of the media | [optional] 
**width** | **str** | Width of the media | [optional] 
**media_format** | **str** | Format of the media | [optional] 

## Example

```python
from entrata_api_client.models.media_item import MediaItem

# TODO update the JSON string below
json = "{}"
# create an instance of MediaItem from a JSON string
media_item_instance = MediaItem.from_json(json)
# print the JSON string representation of the object
print(MediaItem.to_json())

# convert the object into a dict
media_item_dict = media_item_instance.to_dict()
# create an instance of MediaItem from a dict
media_item_from_dict = MediaItem.from_dict(media_item_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


