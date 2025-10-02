# GetQuotesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetQuotesMethodParams**](GetQuotesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_quotes_method import GetQuotesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesMethod from a JSON string
get_quotes_method_instance = GetQuotesMethod.from_json(json)
# print the JSON string representation of the object
print(GetQuotesMethod.to_json())

# convert the object into a dict
get_quotes_method_dict = get_quotes_method_instance.to_dict()
# create an instance of GetQuotesMethod from a dict
get_quotes_method_from_dict = GetQuotesMethod.from_dict(get_quotes_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


