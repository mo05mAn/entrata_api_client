# GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**location_id** | **str** | ID of the location | 
**location_name** | **str** | Name of the location | 
**problems** | [**GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInnerProblems**](GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInnerProblems.md) |  | 

## Example

```python
from entrata_api_client.models.get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner import GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInner from a JSON string
get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner_instance = GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInner.from_json(json)
# print the JSON string representation of the object
print(GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInner.to_json())

# convert the object into a dict
get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner_dict = get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner_instance.to_dict()
# create an instance of GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInner from a dict
get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner_from_dict = GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInner.from_dict(get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


