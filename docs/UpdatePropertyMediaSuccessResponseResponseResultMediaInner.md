# UpdatePropertyMediaSuccessResponseResponseResultMediaInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | Node number of the media in request | 
**id** | **str** | ID of the updated media | 
**status** | **str** | Status of the media update | 
**message** | **str** | Detailed message about the operation | 

## Example

```python
from openapi_client.models.update_property_media_success_response_response_result_media_inner import UpdatePropertyMediaSuccessResponseResponseResultMediaInner

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePropertyMediaSuccessResponseResponseResultMediaInner from a JSON string
update_property_media_success_response_response_result_media_inner_instance = UpdatePropertyMediaSuccessResponseResponseResultMediaInner.from_json(json)
# print the JSON string representation of the object
print(UpdatePropertyMediaSuccessResponseResponseResultMediaInner.to_json())

# convert the object into a dict
update_property_media_success_response_response_result_media_inner_dict = update_property_media_success_response_response_result_media_inner_instance.to_dict()
# create an instance of UpdatePropertyMediaSuccessResponseResponseResultMediaInner from a dict
update_property_media_success_response_response_result_media_inner_from_dict = UpdatePropertyMediaSuccessResponseResponseResultMediaInner.from_dict(update_property_media_success_response_response_result_media_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


