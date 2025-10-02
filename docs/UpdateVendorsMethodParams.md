# UpdateVendorsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendor_id** | **int** | This is a required field. This field accepts single value. | 
**name_on_tax_return** | **str** | This is a required field. This field accepts single value | 
**name** | **str** | This is a required field. This field accepts single value. Accepts locations name. | 
**legal_entity_name** | **str** | This is a required field. This field accepts single value. required if new location is inserted | 
**property_id** | **int** | This is a required field. This field accepts single value. attribute compliance_status_id is required to make the property compli ant/non compliant, Accept integer value 2( for non-compliant) or 5 (fo r compliant) only. | 
**remittance_name** | **str** | This is a required field. This field accepts single value. | 
**name_on_account** | **str** | This is a required field. This field accepts single value. required, if Remittance Type is ACH (eCheck) (i.e. apPaymentTypeId &#x3D; 5 ) | 
**routing_number** | **int** | This is a required field. This field accepts single value. required, if Remittance Type is ACH (eCheck) (i.e. apPaymentTypeId &#x3D; 5 ) | 
**account_number** | **int** | This is a required field. This field accepts single value. required, if Remittance Type is ACH (eCheck) (i.e. apPaymentTypeId &#x3D; 5 ) | 
**external_id** | **str** | This is a required field. This field accepts single value. externalId | 
**default_routing_tag_id** | **int** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from openapi_client.models.update_vendors_method_params import UpdateVendorsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateVendorsMethodParams from a JSON string
update_vendors_method_params_instance = UpdateVendorsMethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateVendorsMethodParams.to_json())

# convert the object into a dict
update_vendors_method_params_dict = update_vendors_method_params_instance.to_dict()
# create an instance of UpdateVendorsMethodParams from a dict
update_vendors_method_params_from_dict = UpdateVendorsMethodParams.from_dict(update_vendors_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


