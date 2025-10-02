# GetPropertyFeesSuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_fees** | [**List[FeeDetails]**](FeeDetails.md) |  | 
**floor_plan_fees** | [**List[FeeDetails]**](FeeDetails.md) |  | 
**unit_type_fees** | [**List[FeeDetails]**](FeeDetails.md) |  | 
**unit_space_fees** | [**List[FeeDetails]**](FeeDetails.md) |  | 

## Example

```python
from openapi_client.models.get_property_fees_success_response_response_result import GetPropertyFeesSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyFeesSuccessResponseResponseResult from a JSON string
get_property_fees_success_response_response_result_instance = GetPropertyFeesSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetPropertyFeesSuccessResponseResponseResult.to_json())

# convert the object into a dict
get_property_fees_success_response_response_result_dict = get_property_fees_success_response_response_result_instance.to_dict()
# create an instance of GetPropertyFeesSuccessResponseResponseResult from a dict
get_property_fees_success_response_response_result_from_dict = GetPropertyFeesSuccessResponseResponseResult.from_dict(get_property_fees_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


