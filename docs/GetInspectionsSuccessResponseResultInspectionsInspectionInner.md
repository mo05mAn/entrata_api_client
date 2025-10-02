# GetInspectionsSuccessResponseResultInspectionsInspectionInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | ID of the inspection | 
**property_id** | **str** | ID of the property | 
**inspection_type_id** | **str** | ID of the inspection type | 
**inspection_status_type_id** | **str** | ID of the inspection status type | 
**inspection_status_type** | **str** | Status of the inspection | 
**inspection_form_id** | **str** | ID of the inspection form | 
**scheduled_date** | **date** | Scheduled date for the inspection | 
**due_date** | **date** | Due date for the inspection | 
**lease_id** | **str** | Lease ID related to the inspection | 
**unit_space_id** | **str** | Unit space ID | 
**note** | **str** | Additional notes for the inspection | 
**locations** | [**GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocations**](GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocations.md) |  | 

## Example

```python
from openapi_client.models.get_inspections_success_response_result_inspections_inspection_inner import GetInspectionsSuccessResponseResultInspectionsInspectionInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionsSuccessResponseResultInspectionsInspectionInner from a JSON string
get_inspections_success_response_result_inspections_inspection_inner_instance = GetInspectionsSuccessResponseResultInspectionsInspectionInner.from_json(json)
# print the JSON string representation of the object
print(GetInspectionsSuccessResponseResultInspectionsInspectionInner.to_json())

# convert the object into a dict
get_inspections_success_response_result_inspections_inspection_inner_dict = get_inspections_success_response_result_inspections_inspection_inner_instance.to_dict()
# create an instance of GetInspectionsSuccessResponseResultInspectionsInspectionInner from a dict
get_inspections_success_response_result_inspections_inspection_inner_from_dict = GetInspectionsSuccessResponseResultInspectionsInspectionInner.from_dict(get_inspections_success_response_result_inspections_inspection_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


