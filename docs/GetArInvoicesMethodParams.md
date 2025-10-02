# GetArInvoicesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**lease_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. leaseIds | [optional] 
**ar_invoice_id** | **int** |   This is an optional field. This field accepts single value. arInvoiceId | [optional] 
**from_date** | **date** | This is an optional field. This field accepts single value. From date. | [optional] 
**to_date** | **date** | This is an optional field. This field accepts single value. To date | [optional] 

## Example

```python
from openapi_client.models.get_ar_invoices_method_params import GetArInvoicesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetArInvoicesMethodParams from a JSON string
get_ar_invoices_method_params_instance = GetArInvoicesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetArInvoicesMethodParams.to_json())

# convert the object into a dict
get_ar_invoices_method_params_dict = get_ar_invoices_method_params_instance.to_dict()
# create an instance of GetArInvoicesMethodParams from a dict
get_ar_invoices_method_params_from_dict = GetArInvoicesMethodParams.from_dict(get_ar_invoices_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


