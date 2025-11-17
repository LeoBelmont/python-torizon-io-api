# PaginationResultComToradexApiGwDataNetworkInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**values** | [**List[NetworkInfo]**](NetworkInfo.md) |  | [optional] 
**total** | **int** |  | 
**offset** | **int** |  | 
**limit** | **int** |  | 

## Example

```python
from torizon_io_api.models.pagination_result_com_toradex_api_gw_data_network_info import PaginationResultComToradexApiGwDataNetworkInfo

# TODO update the JSON string below
json = "{}"
# create an instance of PaginationResultComToradexApiGwDataNetworkInfo from a JSON string
pagination_result_com_toradex_api_gw_data_network_info_instance = PaginationResultComToradexApiGwDataNetworkInfo.from_json(json)
# print the JSON string representation of the object
print(PaginationResultComToradexApiGwDataNetworkInfo.to_json())

# convert the object into a dict
pagination_result_com_toradex_api_gw_data_network_info_dict = pagination_result_com_toradex_api_gw_data_network_info_instance.to_dict()
# create an instance of PaginationResultComToradexApiGwDataNetworkInfo from a dict
pagination_result_com_toradex_api_gw_data_network_info_from_dict = PaginationResultComToradexApiGwDataNetworkInfo.from_dict(pagination_result_com_toradex_api_gw_data_network_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


