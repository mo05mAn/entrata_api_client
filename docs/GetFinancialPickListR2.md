# GetFinancialPickListR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetFinancialPickListR2Method**](GetFinancialPickListR2Method.md) |  | 

## Example

```python
from entrata_api_client.models.get_financial_pick_list_r2 import GetFinancialPickListR2

# TODO update the JSON string below
json = "{}"
# create an instance of GetFinancialPickListR2 from a JSON string
get_financial_pick_list_r2_instance = GetFinancialPickListR2.from_json(json)
# print the JSON string representation of the object
print(GetFinancialPickListR2.to_json())

# convert the object into a dict
get_financial_pick_list_r2_dict = get_financial_pick_list_r2_instance.to_dict()
# create an instance of GetFinancialPickListR2 from a dict
get_financial_pick_list_r2_from_dict = GetFinancialPickListR2.from_dict(get_financial_pick_list_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


