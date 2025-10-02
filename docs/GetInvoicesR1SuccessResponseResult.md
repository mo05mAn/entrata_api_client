# GetInvoicesR1SuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invoices** | [**GetInvoicesR1SuccessResponseResultInvoices**](GetInvoicesR1SuccessResponseResultInvoices.md) |  | 

## Example

```python
from entrata_api_client.models.get_invoices_r1_success_response_result import GetInvoicesR1SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR1SuccessResponseResult from a JSON string
get_invoices_r1_success_response_result_instance = GetInvoicesR1SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR1SuccessResponseResult.to_json())

# convert the object into a dict
get_invoices_r1_success_response_result_dict = get_invoices_r1_success_response_result_instance.to_dict()
# create an instance of GetInvoicesR1SuccessResponseResult from a dict
get_invoices_r1_success_response_result_from_dict = GetInvoicesR1SuccessResponseResult.from_dict(get_invoices_r1_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


