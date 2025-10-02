# GetLeadPickListsR2SuccessResponseResultPsProducts

PS products associated with the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ps_product** | [**List[GetLeadPickListsR2SuccessResponseResultPsProductsPsProductInner]**](GetLeadPickListsR2SuccessResponseResultPsProductsPsProductInner.md) | A list of PS products. | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_pick_lists_r2_success_response_result_ps_products import GetLeadPickListsR2SuccessResponseResultPsProducts

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResultPsProducts from a JSON string
get_lead_pick_lists_r2_success_response_result_ps_products_instance = GetLeadPickListsR2SuccessResponseResultPsProducts.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResultPsProducts.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_ps_products_dict = get_lead_pick_lists_r2_success_response_result_ps_products_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResultPsProducts from a dict
get_lead_pick_lists_r2_success_response_result_ps_products_from_dict = GetLeadPickListsR2SuccessResponseResultPsProducts.from_dict(get_lead_pick_lists_r2_success_response_result_ps_products_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


