# GenerateQuotes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GenerateQuotesMethod**](GenerateQuotesMethod.md) |  | 

## Example

```python
from openapi_client.models.generate_quotes import GenerateQuotes

# TODO update the JSON string below
json = "{}"
# create an instance of GenerateQuotes from a JSON string
generate_quotes_instance = GenerateQuotes.from_json(json)
# print the JSON string representation of the object
print(GenerateQuotes.to_json())

# convert the object into a dict
generate_quotes_dict = generate_quotes_instance.to_dict()
# create an instance of GenerateQuotes from a dict
generate_quotes_from_dict = GenerateQuotes.from_dict(generate_quotes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


