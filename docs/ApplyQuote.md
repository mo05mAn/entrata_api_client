# ApplyQuote


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**ApplyQuoteMethod**](ApplyQuoteMethod.md) |  | 

## Example

```python
from openapi_client.models.apply_quote import ApplyQuote

# TODO update the JSON string below
json = "{}"
# create an instance of ApplyQuote from a JSON string
apply_quote_instance = ApplyQuote.from_json(json)
# print the JSON string representation of the object
print(ApplyQuote.to_json())

# convert the object into a dict
apply_quote_dict = apply_quote_instance.to_dict()
# create an instance of ApplyQuote from a dict
apply_quote_from_dict = ApplyQuote.from_dict(apply_quote_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


