# UpdateApplication


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateApplicationMethod**](UpdateApplicationMethod.md) |  | 

## Example

```python
from entrata_api_client.models.update_application import UpdateApplication

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateApplication from a JSON string
update_application_instance = UpdateApplication.from_json(json)
# print the JSON string representation of the object
print(UpdateApplication.to_json())

# convert the object into a dict
update_application_dict = update_application_instance.to_dict()
# create an instance of UpdateApplication from a dict
update_application_from_dict = UpdateApplication.from_dict(update_application_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


