# SendLeaseActivitiesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property id | 
**lease_id** | **int** | This is a required field. This field accepts single value. leaseId | 
**event_type_id** | **int** | This is a required field. This field accepts single value. Acceptable values are: 8,335,4,436,5,6,15,56. 4 for \&quot;Call-Outgoing\&quot; , 5 for \&quot;Text-Incoming\&quot;, 6 for \&quot;Text-Outgoing\&quot;, 8 for \&quot;Notes\&quot;, 335 fo r \&quot;Lease Retrieved By Collections Agency\&quot;, 436 for \&quot;Hazard Notes\&quot;, 15 for \&quot;Scheduled Follow-Up\&quot;, 56 for \&quot;Delinquency Notes\&quot;. | 
**event_date_time** | **date** | This is a required field. This field accepts single value. | 
**comment** | **str** | This is an optional field. This field accepts single value. This becomes mandatory if eventTypeId is either 4,5, or 6. | [optional] 
**hazard_end_date** | **date** |   This is an optional field. This field accepts single value. This would give end date for the hazard note. | [optional] 
**hazard_note** | **str** | This is a required field. This field accepts single value. This would add note when creating hazard event. | 
**lease_interval_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**leasing_agent_id** | **int** | This is an optional field. This field accepts single value. This becomes mandatory if eventTypeId is 15. | [optional] 
**event_result_id** | **int** | his is an optional field. This field accepts single value. This becomes mandatory if eventTypeId is either 4,5, or 6. | [optional] 
**customer_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**schedule_date_time** | **date** | This is an optional field. This field accepts single value. This becomes mandatory if eventTypeId is 15. | [optional] 

## Example

```python
from entrata_api_client.models.send_lease_activities_method_params import SendLeaseActivitiesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseActivitiesMethodParams from a JSON string
send_lease_activities_method_params_instance = SendLeaseActivitiesMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendLeaseActivitiesMethodParams.to_json())

# convert the object into a dict
send_lease_activities_method_params_dict = send_lease_activities_method_params_instance.to_dict()
# create an instance of SendLeaseActivitiesMethodParams from a dict
send_lease_activities_method_params_from_dict = SendLeaseActivitiesMethodParams.from_dict(send_lease_activities_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


