# SendPropertyMediaSuccessResponseResponseResultMediaInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | Node number of the media in request | 
**id** | **int** | ID of the newly created media | 
**status** | **str** | Status of the media insertion | 
**message** | **str** | Detailed message about the operation | 

## Example

```python
from openapi_client.models.send_property_media_success_response_response_result_media_inner import SendPropertyMediaSuccessResponseResponseResultMediaInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendPropertyMediaSuccessResponseResponseResultMediaInner from a JSON string
send_property_media_success_response_response_result_media_inner_instance = SendPropertyMediaSuccessResponseResponseResultMediaInner.from_json(json)
# print the JSON string representation of the object
print(SendPropertyMediaSuccessResponseResponseResultMediaInner.to_json())

# convert the object into a dict
send_property_media_success_response_response_result_media_inner_dict = send_property_media_success_response_response_result_media_inner_instance.to_dict()
# create an instance of SendPropertyMediaSuccessResponseResponseResultMediaInner from a dict
send_property_media_success_response_response_result_media_inner_from_dict = SendPropertyMediaSuccessResponseResponseResultMediaInner.from_dict(send_property_media_success_response_response_result_media_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


