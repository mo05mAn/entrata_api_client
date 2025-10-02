# GenerateQuotesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. This will fetch quotes associated with the property. | 
**application_id** | **int** | This is an optional field. This field accepts single value. This will fetch quotes associated with the property and the application. | [optional] 
**adjustments_and_provision_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. adjustmentsAndProvisionIds | [optional] 

## Example

```python
from entrata_api_client.models.generate_quotes_method_params import GenerateQuotesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GenerateQuotesMethodParams from a JSON string
generate_quotes_method_params_instance = GenerateQuotesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GenerateQuotesMethodParams.to_json())

# convert the object into a dict
generate_quotes_method_params_dict = generate_quotes_method_params_instance.to_dict()
# create an instance of GenerateQuotesMethodParams from a dict
generate_quotes_method_params_from_dict = GenerateQuotesMethodParams.from_dict(generate_quotes_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


