# GetWebsitesSuccessResponseResultWebsitesWebsiteInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | ID of the website | 
**name** | **str** | Name of the website | 
**subdomain** | **str** | Subdomain of the website | 
**is_corporate_website** | **int** | Indicates if the website is corporate | 
**website_properties** | [**GetWebsitesSuccessResponseResultWebsitesWebsiteInnerWebsiteProperties**](GetWebsitesSuccessResponseResultWebsitesWebsiteInnerWebsiteProperties.md) |  | 
**website_domains** | [**GetWebsitesSuccessResponseResultWebsitesWebsiteInnerWebsiteDomains**](GetWebsitesSuccessResponseResultWebsitesWebsiteInnerWebsiteDomains.md) |  | 

## Example

```python
from openapi_client.models.get_websites_success_response_result_websites_website_inner import GetWebsitesSuccessResponseResultWebsitesWebsiteInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetWebsitesSuccessResponseResultWebsitesWebsiteInner from a JSON string
get_websites_success_response_result_websites_website_inner_instance = GetWebsitesSuccessResponseResultWebsitesWebsiteInner.from_json(json)
# print the JSON string representation of the object
print(GetWebsitesSuccessResponseResultWebsitesWebsiteInner.to_json())

# convert the object into a dict
get_websites_success_response_result_websites_website_inner_dict = get_websites_success_response_result_websites_website_inner_instance.to_dict()
# create an instance of GetWebsitesSuccessResponseResultWebsitesWebsiteInner from a dict
get_websites_success_response_result_websites_website_inner_from_dict = GetWebsitesSuccessResponseResultWebsitesWebsiteInner.from_dict(get_websites_success_response_result_websites_website_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


