# OrgsV1PropertyunitsPostRequestInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**UpdatePropertyMediaAuth**](UpdatePropertyMediaAuth.md) |  | 
**request_id** | **str** | An arbitrary value to relate with response | [optional] 
**method** | [**UpdateSpecialGroupMethod**](UpdateSpecialGroupMethod.md) |  | 

## Example

```python
from entrata_api_client.models.orgs_v1_propertyunits_post_request_inner import OrgsV1PropertyunitsPostRequestInner

# TODO update the JSON string below
json = "{}"
# create an instance of OrgsV1PropertyunitsPostRequestInner from a JSON string
orgs_v1_propertyunits_post_request_inner_instance = OrgsV1PropertyunitsPostRequestInner.from_json(json)
# print the JSON string representation of the object
print(OrgsV1PropertyunitsPostRequestInner.to_json())

# convert the object into a dict
orgs_v1_propertyunits_post_request_inner_dict = orgs_v1_propertyunits_post_request_inner_instance.to_dict()
# create an instance of OrgsV1PropertyunitsPostRequestInner from a dict
orgs_v1_propertyunits_post_request_inner_from_dict = OrgsV1PropertyunitsPostRequestInner.from_dict(orgs_v1_propertyunits_post_request_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


