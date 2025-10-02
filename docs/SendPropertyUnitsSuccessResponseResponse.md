# SendPropertyUnitsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Successful response code. | 
**result** | [**SendPropertyUnitsSuccessResponseResponseResult**](SendPropertyUnitsSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_property_units_success_response_response import SendPropertyUnitsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendPropertyUnitsSuccessResponseResponse from a JSON string
send_property_units_success_response_response_instance = SendPropertyUnitsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SendPropertyUnitsSuccessResponseResponse.to_json())

# convert the object into a dict
send_property_units_success_response_response_dict = send_property_units_success_response_response_instance.to_dict()
# create an instance of SendPropertyUnitsSuccessResponseResponse from a dict
send_property_units_success_response_response_from_dict = SendPropertyUnitsSuccessResponseResponse.from_dict(send_property_units_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


