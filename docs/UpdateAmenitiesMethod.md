# UpdateAmenitiesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**UpdateAmenitiesMethodParams**](UpdateAmenitiesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.update_amenities_method import UpdateAmenitiesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateAmenitiesMethod from a JSON string
update_amenities_method_instance = UpdateAmenitiesMethod.from_json(json)
# print the JSON string representation of the object
print(UpdateAmenitiesMethod.to_json())

# convert the object into a dict
update_amenities_method_dict = update_amenities_method_instance.to_dict()
# create an instance of UpdateAmenitiesMethod from a dict
update_amenities_method_from_dict = UpdateAmenitiesMethod.from_dict(update_amenities_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


