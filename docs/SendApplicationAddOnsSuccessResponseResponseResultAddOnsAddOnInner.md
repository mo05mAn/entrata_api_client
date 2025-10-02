# SendApplicationAddOnsSuccessResponseResponseResultAddOnsAddOnInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Status of the add-on. | 
**message** | **str** | Message related to the add-on. | 
**id** | **int** | ID of the add-on. | 
**add_on_id** | **str** | Unique identifier for the add-on. | 
**node** | **int** | Node number associated with the add-on. | 

## Example

```python
from openapi_client.models.send_application_add_ons_success_response_response_result_add_ons_add_on_inner import SendApplicationAddOnsSuccessResponseResponseResultAddOnsAddOnInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationAddOnsSuccessResponseResponseResultAddOnsAddOnInner from a JSON string
send_application_add_ons_success_response_response_result_add_ons_add_on_inner_instance = SendApplicationAddOnsSuccessResponseResponseResultAddOnsAddOnInner.from_json(json)
# print the JSON string representation of the object
print(SendApplicationAddOnsSuccessResponseResponseResultAddOnsAddOnInner.to_json())

# convert the object into a dict
send_application_add_ons_success_response_response_result_add_ons_add_on_inner_dict = send_application_add_ons_success_response_response_result_add_ons_add_on_inner_instance.to_dict()
# create an instance of SendApplicationAddOnsSuccessResponseResponseResultAddOnsAddOnInner from a dict
send_application_add_ons_success_response_response_result_add_ons_add_on_inner_from_dict = SendApplicationAddOnsSuccessResponseResponseResultAddOnsAddOnInner.from_dict(send_application_add_ons_success_response_response_result_add_ons_add_on_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


