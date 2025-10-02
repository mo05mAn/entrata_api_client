# GenerateQuotesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GenerateQuotesMethodParams**](GenerateQuotesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.generate_quotes_method import GenerateQuotesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GenerateQuotesMethod from a JSON string
generate_quotes_method_instance = GenerateQuotesMethod.from_json(json)
# print the JSON string representation of the object
print(GenerateQuotesMethod.to_json())

# convert the object into a dict
generate_quotes_method_dict = generate_quotes_method_instance.to_dict()
# create an instance of GenerateQuotesMethod from a dict
generate_quotes_method_from_dict = GenerateQuotesMethod.from_dict(generate_quotes_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


