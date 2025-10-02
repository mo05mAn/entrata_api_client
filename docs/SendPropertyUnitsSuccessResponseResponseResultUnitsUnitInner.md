# SendPropertyUnitsSuccessResponseResponseResultUnitsUnitInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | Unique identifier for the unit node | 
**unit_id** | **int** | Unique identifier for the unit | 
**unit_number** | **str** | Unit number | 
**unit_space** | **str** | Space associated with the unit | 
**status** | **str** | Status of the unit operation | 
**message** | **str** | Message about the unit operation | 

## Example

```python
from openapi_client.models.send_property_units_success_response_response_result_units_unit_inner import SendPropertyUnitsSuccessResponseResponseResultUnitsUnitInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendPropertyUnitsSuccessResponseResponseResultUnitsUnitInner from a JSON string
send_property_units_success_response_response_result_units_unit_inner_instance = SendPropertyUnitsSuccessResponseResponseResultUnitsUnitInner.from_json(json)
# print the JSON string representation of the object
print(SendPropertyUnitsSuccessResponseResponseResultUnitsUnitInner.to_json())

# convert the object into a dict
send_property_units_success_response_response_result_units_unit_inner_dict = send_property_units_success_response_response_result_units_unit_inner_instance.to_dict()
# create an instance of SendPropertyUnitsSuccessResponseResponseResultUnitsUnitInner from a dict
send_property_units_success_response_response_result_units_unit_inner_from_dict = SendPropertyUnitsSuccessResponseResponseResultUnitsUnitInner.from_dict(send_property_units_success_response_response_result_units_unit_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


