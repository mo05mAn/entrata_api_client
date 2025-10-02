# SendAmenitiesSuccessResponseResponseResultUnitAmenitiesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | Unique identifier for the unit amenity node | 
**status** | **str** | Status of the unit amenity operation | 
**amenity_id** | **int** | Unique identifier for the unit amenity | 
**rate_association_id** | **int** | Unique identifier for the rate association | 
**name** | **str** | Name of the unit amenity | 
**message** | **str** | Message about the unit amenity operation | 

## Example

```python
from entrata_api_client.models.send_amenities_success_response_response_result_unit_amenities_inner import SendAmenitiesSuccessResponseResponseResultUnitAmenitiesInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendAmenitiesSuccessResponseResponseResultUnitAmenitiesInner from a JSON string
send_amenities_success_response_response_result_unit_amenities_inner_instance = SendAmenitiesSuccessResponseResponseResultUnitAmenitiesInner.from_json(json)
# print the JSON string representation of the object
print(SendAmenitiesSuccessResponseResponseResultUnitAmenitiesInner.to_json())

# convert the object into a dict
send_amenities_success_response_response_result_unit_amenities_inner_dict = send_amenities_success_response_response_result_unit_amenities_inner_instance.to_dict()
# create an instance of SendAmenitiesSuccessResponseResponseResultUnitAmenitiesInner from a dict
send_amenities_success_response_response_result_unit_amenities_inner_from_dict = SendAmenitiesSuccessResponseResponseResultUnitAmenitiesInner.from_dict(send_amenities_success_response_response_result_unit_amenities_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


