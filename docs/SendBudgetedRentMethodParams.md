# SendBudgetedRentMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**pricing_level_id** | **int** |   This is a required field. This field accepts single value. Pricing level has two possible values, 3 for Unit type and 4 for Unit space. | 
**pricing_level_reference_id** | **int** | This is a required field. This field accepts single value. This is Entrata&#x60;s record id depending on #pricingLevelId. E.g. If pric ingLevelId &#x3D; 3 then pricingLevelReferenceId needs to be unit type id a nd if pricingLevelId &#x3D; 4 then pricingLevelReferenceId needs to be unit space id. | 
**amenity_amount** | **int** | This is an optional field. This field accepts single value. Amenity rate amount. | [optional] 
**amount** | **int** | This is a required field. This field accepts single value. amount | 

## Example

```python
from entrata_api_client.models.send_budgeted_rent_method_params import SendBudgetedRentMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetedRentMethodParams from a JSON string
send_budgeted_rent_method_params_instance = SendBudgetedRentMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendBudgetedRentMethodParams.to_json())

# convert the object into a dict
send_budgeted_rent_method_params_dict = send_budgeted_rent_method_params_instance.to_dict()
# create an instance of SendBudgetedRentMethodParams from a dict
send_budgeted_rent_method_params_from_dict = SendBudgetedRentMethodParams.from_dict(send_budgeted_rent_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


