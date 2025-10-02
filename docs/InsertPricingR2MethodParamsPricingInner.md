# InsertPricingR2MethodParamsPricingInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pricing_level_id** | **int** | This is a required field. This field accepts single value. Pricing level has four possible values, 1: property, 2: floor plan 3: Unit type 4: Unit space. | 
**pricing_level_reference_id** | **int** | This is a required field. This field accepts single value. This is Entrata&#x60;s record id depending on #pricingLevelId. | 
**charge_usage_id** | **int** | This is a required field. This field accepts single value. This helps to differentiate pricing usage. 1. Base 2: Amenity 3: Pet 4: Add-Ons 5: Risk Premium 7: Maintenance | 
**is_renewal** | **int** | This is an optional field. This field accepts single value. Just to specify if it is renewal rent. | [optional] 
**charge_timing_id** | **int** | This is a required field. This field accepts single value. This explains when charge suppose to apply [charge trigger timing]. | 
**charge_code_type_id** | **int** | This is a required field. This field accepts single value. This explains charge code types. 1: Payment 2: Rent 3: Other Income 7: Deposit | 
**charge_code_id** | **int** | This is a required field. This field accepts single value. This is Entrata charge code id which we want to use. | 
**lease_term_months** | **int** | This is an optional field. This field accepts single value. Most of the cases it will be zero but if the property has the setup to have term wise pricing/rent then you can send the different pricing for different terms. | [optional] 
**lease_term_id** | **int** | This is an optional field. This field accepts single value. Lease term identifier. | [optional] 
**lease_start_window_id** | **int** | This is an optional field. This field accepts single value. Lease start window identifier. | [optional] 
**space_configuration_id** | **int** | This is an optional field. This field accepts single value. Space configuration identifier. | [optional] 
**lease_term_name** | **str** | This is a required field. This field accepts single value. If there are multiple lease terms with same length then this node is mandatory. | 
**lease_start_range_start** | **date** | This is an optional field. This field accepts single value. This nodes allows to send different rent amount for different move in dates but with same intervals. | [optional] 
**lease_start_range_end** | **date** | This is an optional field. This field accepts single value. This nodes allows to send different rent amount for different move in dates but with the same intervals. | [optional] 
**amount** | **str** | This is a required field. This field accepts single value. Rate Amount. | 
**is_full_update** | **str** | This is an optional field. This field accepts single value. Indicates if this is a full update operation. | [optional] 

## Example

```python
from openapi_client.models.insert_pricing_r2_method_params_pricing_inner import InsertPricingR2MethodParamsPricingInner

# TODO update the JSON string below
json = "{}"
# create an instance of InsertPricingR2MethodParamsPricingInner from a JSON string
insert_pricing_r2_method_params_pricing_inner_instance = InsertPricingR2MethodParamsPricingInner.from_json(json)
# print the JSON string representation of the object
print(InsertPricingR2MethodParamsPricingInner.to_json())

# convert the object into a dict
insert_pricing_r2_method_params_pricing_inner_dict = insert_pricing_r2_method_params_pricing_inner_instance.to_dict()
# create an instance of InsertPricingR2MethodParamsPricingInner from a dict
insert_pricing_r2_method_params_pricing_inner_from_dict = InsertPricingR2MethodParamsPricingInner.from_dict(insert_pricing_r2_method_params_pricing_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


