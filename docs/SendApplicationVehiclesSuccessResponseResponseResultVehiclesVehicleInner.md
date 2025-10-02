# SendApplicationVehiclesSuccessResponseResponseResultVehiclesVehicleInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Status of the vehicle operation. | 
**message** | **str** | Message indicating the vehicle operation result. | 
**id** | **int** | Vehicle ID. | 
**customer_id** | **int** | Customer ID. | 
**vehicle_type_id** | **int** | Type ID of the vehicle. | 
**node** | **int** | Node number associated with the vehicle. | 

## Example

```python
from openapi_client.models.send_application_vehicles_success_response_response_result_vehicles_vehicle_inner import SendApplicationVehiclesSuccessResponseResponseResultVehiclesVehicleInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationVehiclesSuccessResponseResponseResultVehiclesVehicleInner from a JSON string
send_application_vehicles_success_response_response_result_vehicles_vehicle_inner_instance = SendApplicationVehiclesSuccessResponseResponseResultVehiclesVehicleInner.from_json(json)
# print the JSON string representation of the object
print(SendApplicationVehiclesSuccessResponseResponseResultVehiclesVehicleInner.to_json())

# convert the object into a dict
send_application_vehicles_success_response_response_result_vehicles_vehicle_inner_dict = send_application_vehicles_success_response_response_result_vehicles_vehicle_inner_instance.to_dict()
# create an instance of SendApplicationVehiclesSuccessResponseResponseResultVehiclesVehicleInner from a dict
send_application_vehicles_success_response_response_result_vehicles_vehicle_inner_from_dict = SendApplicationVehiclesSuccessResponseResponseResultVehiclesVehicleInner.from_dict(send_application_vehicles_success_response_response_result_vehicles_vehicle_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


