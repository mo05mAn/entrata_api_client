# UpdateInvoicesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | This is a required field. This field accepts single value. Accepts apHeader id,apDetail id | 
**invoice_payment_id** | **int** | This is a required field. This field accepts single value. | 
**payment_amount** | **int** | This is a required field. This field accepts single value. | 
**payment_type_id** | **int** | This is a required field. This field accepts single value. | 
**payment_number** | **str** | This is a required field. This field accepts single value. | 
**payment_date** | **date** | This is a required field. This field accepts single value. | 
**post_month** | **date** | This is a required field. This field accepts single value. | 
**is_on_hold** | **int** | This is an optional field. This field accepts single value. Update an invoice that is on hold, and take it off hold, and vice vers a, Allowed values ( 0, 1 ) | [optional] 
**routing_tag_id** | **int** | This is an optional field. This field accepts single value. Update the routing tag on an invoice, to another valid routing tag. Al low for not posted and off hold invoice. | [optional] 

## Example

```python
from openapi_client.models.update_invoices_method_params import UpdateInvoicesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateInvoicesMethodParams from a JSON string
update_invoices_method_params_instance = UpdateInvoicesMethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateInvoicesMethodParams.to_json())

# convert the object into a dict
update_invoices_method_params_dict = update_invoices_method_params_instance.to_dict()
# create an instance of UpdateInvoicesMethodParams from a dict
update_invoices_method_params_from_dict = UpdateInvoicesMethodParams.from_dict(update_invoices_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


