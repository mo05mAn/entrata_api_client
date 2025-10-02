# GetPricingPicklists


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetPricingPicklistsMethod**](GetPricingPicklistsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_pricing_picklists import GetPricingPicklists

# TODO update the JSON string below
json = "{}"
# create an instance of GetPricingPicklists from a JSON string
get_pricing_picklists_instance = GetPricingPicklists.from_json(json)
# print the JSON string representation of the object
print(GetPricingPicklists.to_json())

# convert the object into a dict
get_pricing_picklists_dict = get_pricing_picklists_instance.to_dict()
# create an instance of GetPricingPicklists from a dict
get_pricing_picklists_from_dict = GetPricingPicklists.from_dict(get_pricing_picklists_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


