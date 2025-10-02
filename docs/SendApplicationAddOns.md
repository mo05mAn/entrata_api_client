# SendApplicationAddOns


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendApplicationAddOnsMethod**](SendApplicationAddOnsMethod.md) |  | 

## Example

```python
from openapi_client.models.send_application_add_ons import SendApplicationAddOns

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationAddOns from a JSON string
send_application_add_ons_instance = SendApplicationAddOns.from_json(json)
# print the JSON string representation of the object
print(SendApplicationAddOns.to_json())

# convert the object into a dict
send_application_add_ons_dict = send_application_add_ons_instance.to_dict()
# create an instance of SendApplicationAddOns from a dict
send_application_add_ons_from_dict = SendApplicationAddOns.from_dict(send_application_add_ons_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


