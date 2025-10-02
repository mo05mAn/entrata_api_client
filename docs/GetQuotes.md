# GetQuotes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetQuotesMethod**](GetQuotesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_quotes import GetQuotes

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotes from a JSON string
get_quotes_instance = GetQuotes.from_json(json)
# print the JSON string representation of the object
print(GetQuotes.to_json())

# convert the object into a dict
get_quotes_dict = get_quotes_instance.to_dict()
# create an instance of GetQuotes from a dict
get_quotes_from_dict = GetQuotes.from_dict(get_quotes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


