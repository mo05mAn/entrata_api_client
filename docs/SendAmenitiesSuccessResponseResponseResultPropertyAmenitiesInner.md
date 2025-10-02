# SendAmenitiesSuccessResponseResponseResultPropertyAmenitiesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | Unique identifier for the amenity node | 
**status** | **str** | Status of the amenity operation | 
**amenity_id** | **int** | Unique identifier for the property amenity | 
**rate_association_id** | **int** | Unique identifier for the rate association | 
**name** | **str** | Name of the property amenity | 
**message** | **str** | Message about the amenity operation | 

## Example

```python
from openapi_client.models.send_amenities_success_response_response_result_property_amenities_inner import SendAmenitiesSuccessResponseResponseResultPropertyAmenitiesInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendAmenitiesSuccessResponseResponseResultPropertyAmenitiesInner from a JSON string
send_amenities_success_response_response_result_property_amenities_inner_instance = SendAmenitiesSuccessResponseResponseResultPropertyAmenitiesInner.from_json(json)
# print the JSON string representation of the object
print(SendAmenitiesSuccessResponseResponseResultPropertyAmenitiesInner.to_json())

# convert the object into a dict
send_amenities_success_response_response_result_property_amenities_inner_dict = send_amenities_success_response_response_result_property_amenities_inner_instance.to_dict()
# create an instance of SendAmenitiesSuccessResponseResponseResultPropertyAmenitiesInner from a dict
send_amenities_success_response_response_result_property_amenities_inner_from_dict = SendAmenitiesSuccessResponseResponseResultPropertyAmenitiesInner.from_dict(send_amenities_success_response_response_result_property_amenities_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


