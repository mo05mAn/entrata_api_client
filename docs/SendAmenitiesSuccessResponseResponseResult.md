# SendAmenitiesSuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_amenities** | [**List[SendAmenitiesSuccessResponseResponseResultPropertyAmenitiesInner]**](SendAmenitiesSuccessResponseResponseResultPropertyAmenitiesInner.md) | List of property amenities | 
**unit_amenities** | [**List[SendAmenitiesSuccessResponseResponseResultUnitAmenitiesInner]**](SendAmenitiesSuccessResponseResponseResultUnitAmenitiesInner.md) | List of unit amenities | 

## Example

```python
from openapi_client.models.send_amenities_success_response_response_result import SendAmenitiesSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendAmenitiesSuccessResponseResponseResult from a JSON string
send_amenities_success_response_response_result_instance = SendAmenitiesSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendAmenitiesSuccessResponseResponseResult.to_json())

# convert the object into a dict
send_amenities_success_response_response_result_dict = send_amenities_success_response_response_result_instance.to_dict()
# create an instance of SendAmenitiesSuccessResponseResponseResult from a dict
send_amenities_success_response_response_result_from_dict = SendAmenitiesSuccessResponseResponseResult.from_dict(send_amenities_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


