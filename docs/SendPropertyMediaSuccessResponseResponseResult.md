# SendPropertyMediaSuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**media** | [**List[SendPropertyMediaSuccessResponseResponseResultMediaInner]**](SendPropertyMediaSuccessResponseResponseResultMediaInner.md) |  | 

## Example

```python
from entrata_api_client.models.send_property_media_success_response_response_result import SendPropertyMediaSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendPropertyMediaSuccessResponseResponseResult from a JSON string
send_property_media_success_response_response_result_instance = SendPropertyMediaSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendPropertyMediaSuccessResponseResponseResult.to_json())

# convert the object into a dict
send_property_media_success_response_response_result_dict = send_property_media_success_response_response_result_instance.to_dict()
# create an instance of SendPropertyMediaSuccessResponseResponseResult from a dict
send_property_media_success_response_response_result_from_dict = SendPropertyMediaSuccessResponseResponseResult.from_dict(send_property_media_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


