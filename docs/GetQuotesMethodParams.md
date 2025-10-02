# GetQuotesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. This will fetch quotes associated with the property. | 
**application_id** | **int** | This is an optional field. This field accepts single value. This will fetch quotes associated with the property and the application. | [optional] 
**lease_start_date** | **date** | This is an optional field. This field accepts single value. Format: MM/DD/YYYY, YYYY-MM-DD, MM/DD/YY | [optional] 
**quote_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**include_expired_quotes** | **int** | This is an optional field. This field accepts single value. If pass value \&quot;1\&quot; then expired quotes should get returned in the response. | [optional] 

## Example

```python
from entrata_api_client.models.get_quotes_method_params import GetQuotesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesMethodParams from a JSON string
get_quotes_method_params_instance = GetQuotesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetQuotesMethodParams.to_json())

# convert the object into a dict
get_quotes_method_params_dict = get_quotes_method_params_instance.to_dict()
# create an instance of GetQuotesMethodParams from a dict
get_quotes_method_params_from_dict = GetQuotesMethodParams.from_dict(get_quotes_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


