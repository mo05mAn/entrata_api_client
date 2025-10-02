# GetWorkOrderPickListsSuccessResponseResultPropertyLocationsLocationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | ID of the location | 
**name** | **str** | Name of the location | 
**type** | **str** | Type of the location | 
**is_resident_portal_enabled** | **str** | Indicates if the location is enabled on the resident portal | 
**unit_types** | [**GetWorkOrderPickListsSuccessResponseResultPropertyLocationsLocationInnerUnitTypes**](GetWorkOrderPickListsSuccessResponseResultPropertyLocationsLocationInnerUnitTypes.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_work_order_pick_lists_success_response_result_property_locations_location_inner import GetWorkOrderPickListsSuccessResponseResultPropertyLocationsLocationInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrderPickListsSuccessResponseResultPropertyLocationsLocationInner from a JSON string
get_work_order_pick_lists_success_response_result_property_locations_location_inner_instance = GetWorkOrderPickListsSuccessResponseResultPropertyLocationsLocationInner.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrderPickListsSuccessResponseResultPropertyLocationsLocationInner.to_json())

# convert the object into a dict
get_work_order_pick_lists_success_response_result_property_locations_location_inner_dict = get_work_order_pick_lists_success_response_result_property_locations_location_inner_instance.to_dict()
# create an instance of GetWorkOrderPickListsSuccessResponseResultPropertyLocationsLocationInner from a dict
get_work_order_pick_lists_success_response_result_property_locations_location_inner_from_dict = GetWorkOrderPickListsSuccessResponseResultPropertyLocationsLocationInner.from_dict(get_work_order_pick_lists_success_response_result_property_locations_location_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


