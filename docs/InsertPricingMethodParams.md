# InsertPricingMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pricing_level_id** | **int** | This is a required field. This field accepts single value. Pricing level has four possible values, 1: property, 2: floor plan 3: Unit type 4: Unit space. | 
**pricing_level_reference_id** | **int** | This is a required field. This field accepts single value. This is Entrata&#x60;s record id depending on #pricingLevelId. E.g. If pric ingLevelId &#x3D; 4 then pricingLevelReferenceId needs to be unit space id. | 
**charge_usage_id** | **int** | This is a required field. This field accepts single value. This helps to differentiate pricing usage. 1. Base 2: Amenity 3: Pet 4: Add-Ons 5: Risk Premium 7: Maintenance | 
**charge_usage_reference_id** | **int** | This is a required field. This field accepts single value. This value needs to set if needs to update pricing any other than base rent. E.g if want to update amenity rent then chargeUsageReferenceId should amenity id. In the case of base pricing, it needs to be 0. | 
**is_renewal** | **int** | This is an optional field. This field accepts single value. Just to specify if it is renewal rent. | [optional] 
**charge_timing_id** | **int** | This is a required field. This field accepts single value. This explains when charge suppose to apply [charge trigger timing]. E .g. There are a number of possible values but common is 307: Monthly 202: Move In 206: Move Out 102: Application Completed | 
**charge_code_type_id** | **int** | This is a required field. This field accepts single value. This explains charge code types. 1: Payment 2: Rent 3: Other Income 7: Deposit | 
**charge_code_id** | **int** | This is a required field. This field accepts single value. This is Entrata charge code id which we want to use. | 
**lease_term_months** | **int** | This is an optional field. This field accepts single value. Most of the cases it will be zero but if the property has the setup to have term wise pricing/rent then you can send the different pricing f or different terms. Zero means single value for all lease terms. | [optional] 
**lease_start_range_start** | **int** | This is an optional field. This field accepts single value. This nodes allows to send different rent amount for different move in dates but with same intervals. Refer Property setting: Price By Lease Start Range. E.g Property has pricing setup to have 3 days interval pricing then data can looks like, leaseStartRangeStart:0 leaseStartRa ngeEnd:2 amount:700 Zero represents current date or unit&#x60;s available on the date [if available on a date is in future]. If sending \&quot;isRenewal\&quot; as true this value should always be sent as 0 | [optional] 
**lease_start_range_end** | **int** | This is an optional field. This field accepts single value. This nodes allows to send different rent amount for different move in dates but with the same intervals. E.g Property has pricing setup to have 3 days interval pricing then data can look like, leaseStartRange Start:0 leaseStartRangeEnd:2 amount:700. If sending \&quot;isRenewal\&quot; as true this value should always be sent as 0 | [optional] 
**amount** | **int** | This is a required field. This field accepts single value. Rate Amount. | 
**lease_term_name** | **str** | This is a required field. This field accepts single value. If there are multiple lease terms with same length then this node is m andatory. | 

## Example

```python
from openapi_client.models.insert_pricing_method_params import InsertPricingMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of InsertPricingMethodParams from a JSON string
insert_pricing_method_params_instance = InsertPricingMethodParams.from_json(json)
# print the JSON string representation of the object
print(InsertPricingMethodParams.to_json())

# convert the object into a dict
insert_pricing_method_params_dict = insert_pricing_method_params_instance.to_dict()
# create an instance of InsertPricingMethodParams from a dict
insert_pricing_method_params_from_dict = InsertPricingMethodParams.from_dict(insert_pricing_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


