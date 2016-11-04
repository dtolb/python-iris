# swagger_client
No descripton provided (generated by Swagger Codegen https://github.com/swagger-api/swagger-codegen)

This Python package is automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) project:

- API version: v1
- Package version: 1.0.0
- Build date: 2016-11-04T19:41:03.006Z
- Build package: class io.swagger.codegen.languages.PythonClientCodegen

## Requirements.

Python 2.7 and 3.4+

## Installation & Usage
### pip install

If the python package is hosted on Github, you can install directly from Github

```sh
pip install git+https://github.com//.git
```
(you may need to run `pip` with root permission: `sudo pip install git+https://github.com//.git`)

Then import the package:
```python
import swagger_client 
```

### Setuptools

Install via [Setuptools](http://pypi.python.org/pypi/setuptools).

```sh
python setup.py install --user
```
(or `sudo python setup.py install` to install the package for all users)

Then import the package:
```python
import swagger_client
```

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```python
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint
# create an instance of the API class
api_instance = swagger_client.DefaultApi
account_id = 'account_id_example' # str | 
area_code = 56 # int | The allowed number ranges are [2-9] for the first digit and [0-9] for both the second and third digits. (optional)
state = 'state_example' # str | Returns only the NPA NXX information within the specified state (optional)
quantity = 56 # int | Filters out any Npa-Nxx grouped phone numbers whose quantity falls short of the given quantity. (optional)

try:
    api_instance.accounts_account_id_available_npa_nxx_get(account_id, area_code=area_code, state=state, quantity=quantity)
except ApiException as e:
    print "Exception when calling DefaultApi->accounts_account_id_available_npa_nxx_get: %s\n" % e

```

## Documentation for API Endpoints

All URIs are relative to *http://null/*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**accounts_account_id_available_npa_nxx_get**](docs/DefaultApi.md#accounts_account_id_available_npa_nxx_get) | **GET** /accounts/{accountId}/availableNpaNxx | 
*DefaultApi* | [**accounts_account_id_available_numbers_get**](docs/DefaultApi.md#accounts_account_id_available_numbers_get) | **GET** /accounts/{accountId}/availableNumbers | 
*DefaultApi* | [**accounts_account_id_bdrs_bdrid_file_get**](docs/DefaultApi.md#accounts_account_id_bdrs_bdrid_file_get) | **GET** /accounts/{accountId}/bdrs/{bdrid}/file | 
*DefaultApi* | [**accounts_account_id_bdrs_bdrid_get**](docs/DefaultApi.md#accounts_account_id_bdrs_bdrid_get) | **GET** /accounts/{accountId}/bdrs/{bdrid} | 
*DefaultApi* | [**accounts_account_id_bdrs_post**](docs/DefaultApi.md#accounts_account_id_bdrs_post) | **POST** /accounts/{accountId}/bdrs | 
*DefaultApi* | [**accounts_account_id_billingreports_post**](docs/DefaultApi.md#accounts_account_id_billingreports_post) | **POST** /accounts/{accountId}/billingreports | 
*DefaultApi* | [**accounts_account_id_billingreports_reportid_file_get**](docs/DefaultApi.md#accounts_account_id_billingreports_reportid_file_get) | **GET** /accounts/{accountId}/billingreports/{reportid}/file | 
*DefaultApi* | [**accounts_account_id_billingreports_reportid_get**](docs/DefaultApi.md#accounts_account_id_billingreports_reportid_get) | **GET** /accounts/{accountId}/billingreports/{reportid} | 
*DefaultApi* | [**accounts_account_id_discnumbers_get**](docs/DefaultApi.md#accounts_account_id_discnumbers_get) | **GET** /accounts/{accountId}/discnumbers | 
*DefaultApi* | [**accounts_account_id_discnumbers_totals_get**](docs/DefaultApi.md#accounts_account_id_discnumbers_totals_get) | **GET** /accounts/{accountId}/discnumbers/totals | 
*DefaultApi* | [**accounts_account_id_disconnects_disconnectid_get**](docs/DefaultApi.md#accounts_account_id_disconnects_disconnectid_get) | **GET** /accounts/{accountId}/disconnects/{disconnectid} | 
*DefaultApi* | [**accounts_account_id_disconnects_disconnectid_notes_get**](docs/DefaultApi.md#accounts_account_id_disconnects_disconnectid_notes_get) | **GET** /accounts/{accountId}/disconnects/{disconnectid}/notes | 
*DefaultApi* | [**accounts_account_id_disconnects_disconnectid_notes_post**](docs/DefaultApi.md#accounts_account_id_disconnects_disconnectid_notes_post) | **POST** /accounts/{accountId}/disconnects/{disconnectid}/notes | 
*DefaultApi* | [**accounts_account_id_disconnects_get**](docs/DefaultApi.md#accounts_account_id_disconnects_get) | **GET** /accounts/{accountId}/disconnects | 
*DefaultApi* | [**accounts_account_id_disconnects_post**](docs/DefaultApi.md#accounts_account_id_disconnects_post) | **POST** /accounts/{accountId}/disconnects | 
*DefaultApi* | [**accounts_account_id_dldas_get**](docs/DefaultApi.md#accounts_account_id_dldas_get) | **GET** /accounts/{accountId}/dldas | 
*DefaultApi* | [**accounts_account_id_dldas_orderid_get**](docs/DefaultApi.md#accounts_account_id_dldas_orderid_get) | **GET** /accounts/{accountId}/dldas/{orderid} | 
*DefaultApi* | [**accounts_account_id_dldas_orderid_history_get**](docs/DefaultApi.md#accounts_account_id_dldas_orderid_history_get) | **GET** /accounts/{accountId}/dldas/{orderid}/history | 
*DefaultApi* | [**accounts_account_id_dldas_orderid_put**](docs/DefaultApi.md#accounts_account_id_dldas_orderid_put) | **PUT** /accounts/{accountId}/dldas/{orderid} | 
*DefaultApi* | [**accounts_account_id_dldas_post**](docs/DefaultApi.md#accounts_account_id_dldas_post) | **POST** /accounts/{accountId}/dldas | 
*DefaultApi* | [**accounts_account_id_e911s_get**](docs/DefaultApi.md#accounts_account_id_e911s_get) | **GET** /accounts/{accountId}/e911s | 
*DefaultApi* | [**accounts_account_id_e911s_orderid_get**](docs/DefaultApi.md#accounts_account_id_e911s_orderid_get) | **GET** /accounts/{accountId}/e911s/{orderid} | 
*DefaultApi* | [**accounts_account_id_e911s_orderid_history_get**](docs/DefaultApi.md#accounts_account_id_e911s_orderid_history_get) | **GET** /accounts/{accountId}/e911s/{orderid}/history | 
*DefaultApi* | [**accounts_account_id_e911s_post**](docs/DefaultApi.md#accounts_account_id_e911s_post) | **POST** /accounts/{accountId}/e911s | 
*DefaultApi* | [**accounts_account_id_external_tns_get**](docs/DefaultApi.md#accounts_account_id_external_tns_get) | **GET** /accounts/{accountId}/externalTns | 
*DefaultApi* | [**accounts_account_id_external_tns_orderid_get**](docs/DefaultApi.md#accounts_account_id_external_tns_orderid_get) | **GET** /accounts/{accountId}/externalTns/{orderid} | 
*DefaultApi* | [**accounts_account_id_external_tns_post**](docs/DefaultApi.md#accounts_account_id_external_tns_post) | **POST** /accounts/{accountId}/externalTns | 
*DefaultApi* | [**accounts_account_id_get**](docs/DefaultApi.md#accounts_account_id_get) | **GET** /accounts/{accountId} | 
*DefaultApi* | [**accounts_account_id_hosts_get**](docs/DefaultApi.md#accounts_account_id_hosts_get) | **GET** /accounts/{accountId}/hosts | 
*DefaultApi* | [**accounts_account_id_inservice_numbers_get**](docs/DefaultApi.md#accounts_account_id_inservice_numbers_get) | **GET** /accounts/{accountId}/inserviceNumbers | 
*DefaultApi* | [**accounts_account_id_inservice_numbers_tn_get**](docs/DefaultApi.md#accounts_account_id_inservice_numbers_tn_get) | **GET** /accounts/{accountId}/inserviceNumbers/{tn} | 
*DefaultApi* | [**accounts_account_id_inservice_numbers_totals_get**](docs/DefaultApi.md#accounts_account_id_inservice_numbers_totals_get) | **GET** /accounts/{accountId}/inserviceNumbers/totals | 
*DefaultApi* | [**accounts_account_id_lidbs_get**](docs/DefaultApi.md#accounts_account_id_lidbs_get) | **GET** /accounts/{accountId}/lidbs | 
*DefaultApi* | [**accounts_account_id_lidbs_lidbid_get**](docs/DefaultApi.md#accounts_account_id_lidbs_lidbid_get) | **GET** /accounts/{accountId}/lidbs/{lidbid} | 
*DefaultApi* | [**accounts_account_id_lidbs_post**](docs/DefaultApi.md#accounts_account_id_lidbs_post) | **POST** /accounts/{accountId}/lidbs | 
*DefaultApi* | [**accounts_account_id_line_option_orders_post**](docs/DefaultApi.md#accounts_account_id_line_option_orders_post) | **POST** /accounts/{accountId}/lineOptionOrders | 
*DefaultApi* | [**accounts_account_id_lnpchecker_post**](docs/DefaultApi.md#accounts_account_id_lnpchecker_post) | **POST** /accounts/{accountId}/lnpchecker | 
*DefaultApi* | [**accounts_account_id_lsrorders_get**](docs/DefaultApi.md#accounts_account_id_lsrorders_get) | **GET** /accounts/{accountId}/lsrorders | 
*DefaultApi* | [**accounts_account_id_lsrorders_orderid_get**](docs/DefaultApi.md#accounts_account_id_lsrorders_orderid_get) | **GET** /accounts/{accountId}/lsrorders/{orderid} | 
*DefaultApi* | [**accounts_account_id_lsrorders_orderid_history_get**](docs/DefaultApi.md#accounts_account_id_lsrorders_orderid_history_get) | **GET** /accounts/{accountId}/lsrorders/{orderid}/history | 
*DefaultApi* | [**accounts_account_id_lsrorders_orderid_notes_get**](docs/DefaultApi.md#accounts_account_id_lsrorders_orderid_notes_get) | **GET** /accounts/{accountId}/lsrorders/{orderid}/notes | 
*DefaultApi* | [**accounts_account_id_lsrorders_orderid_notes_post**](docs/DefaultApi.md#accounts_account_id_lsrorders_orderid_notes_post) | **POST** /accounts/{accountId}/lsrorders/{orderid}/notes | 
*DefaultApi* | [**accounts_account_id_lsrorders_orderid_put**](docs/DefaultApi.md#accounts_account_id_lsrorders_orderid_put) | **PUT** /accounts/{accountId}/lsrorders/{orderid} | 
*DefaultApi* | [**accounts_account_id_lsrorders_post**](docs/DefaultApi.md#accounts_account_id_lsrorders_post) | **POST** /accounts/{accountId}/lsrorders | 
*DefaultApi* | [**accounts_account_id_orders_get**](docs/DefaultApi.md#accounts_account_id_orders_get) | **GET** /accounts/{accountId}/orders | 
*DefaultApi* | [**accounts_account_id_orders_orderid_area_codes_get**](docs/DefaultApi.md#accounts_account_id_orders_orderid_area_codes_get) | **GET** /accounts/{accountId}/orders/{orderid}/areaCodes | 
*DefaultApi* | [**accounts_account_id_orders_orderid_get**](docs/DefaultApi.md#accounts_account_id_orders_orderid_get) | **GET** /accounts/{accountId}/orders/{orderid} | 
*DefaultApi* | [**accounts_account_id_orders_orderid_history_get**](docs/DefaultApi.md#accounts_account_id_orders_orderid_history_get) | **GET** /accounts/{accountId}/orders/{orderid}/history | 
*DefaultApi* | [**accounts_account_id_orders_orderid_notes_get**](docs/DefaultApi.md#accounts_account_id_orders_orderid_notes_get) | **GET** /accounts/{accountId}/orders/{orderid}/notes | 
*DefaultApi* | [**accounts_account_id_orders_orderid_notes_post**](docs/DefaultApi.md#accounts_account_id_orders_orderid_notes_post) | **POST** /accounts/{accountId}/orders/{orderid}/notes | 
*DefaultApi* | [**accounts_account_id_orders_orderid_npa_nxx_get**](docs/DefaultApi.md#accounts_account_id_orders_orderid_npa_nxx_get) | **GET** /accounts/{accountId}/orders/{orderid}/npaNxx | 
*DefaultApi* | [**accounts_account_id_orders_orderid_put**](docs/DefaultApi.md#accounts_account_id_orders_orderid_put) | **PUT** /accounts/{accountId}/orders/{orderid} | 
*DefaultApi* | [**accounts_account_id_orders_orderid_tns_get**](docs/DefaultApi.md#accounts_account_id_orders_orderid_tns_get) | **GET** /accounts/{accountId}/orders/{orderid}/tns | 
*DefaultApi* | [**accounts_account_id_orders_orderid_totals_get**](docs/DefaultApi.md#accounts_account_id_orders_orderid_totals_get) | **GET** /accounts/{accountId}/orders/{orderid}/totals | 
*DefaultApi* | [**accounts_account_id_orders_post**](docs/DefaultApi.md#accounts_account_id_orders_post) | **POST** /accounts/{accountId}/orders | 
*DefaultApi* | [**accounts_account_id_portins_get**](docs/DefaultApi.md#accounts_account_id_portins_get) | **GET** /accounts/{accountId}/portins | 
*DefaultApi* | [**accounts_account_id_portins_orderid_activation_status_get**](docs/DefaultApi.md#accounts_account_id_portins_orderid_activation_status_get) | **GET** /accounts/{accountId}/portins/{orderid}/activationStatus | 
*DefaultApi* | [**accounts_account_id_portins_orderid_activation_status_put**](docs/DefaultApi.md#accounts_account_id_portins_orderid_activation_status_put) | **PUT** /accounts/{accountId}/portins/{orderid}/activationStatus | 
*DefaultApi* | [**accounts_account_id_portins_orderid_area_codes_get**](docs/DefaultApi.md#accounts_account_id_portins_orderid_area_codes_get) | **GET** /accounts/{accountId}/portins/{orderid}/areaCodes | 
*DefaultApi* | [**accounts_account_id_portins_orderid_delete**](docs/DefaultApi.md#accounts_account_id_portins_orderid_delete) | **DELETE** /accounts/{accountId}/portins/{orderid} | 
*DefaultApi* | [**accounts_account_id_portins_orderid_get**](docs/DefaultApi.md#accounts_account_id_portins_orderid_get) | **GET** /accounts/{accountId}/portins/{orderid} | 
*DefaultApi* | [**accounts_account_id_portins_orderid_history_get**](docs/DefaultApi.md#accounts_account_id_portins_orderid_history_get) | **GET** /accounts/{accountId}/portins/{orderid}/history | 
*DefaultApi* | [**accounts_account_id_portins_orderid_loas_fileid_delete**](docs/DefaultApi.md#accounts_account_id_portins_orderid_loas_fileid_delete) | **DELETE** /accounts/{accountId}/portins/{orderid}/loas/{fileid} | 
*DefaultApi* | [**accounts_account_id_portins_orderid_loas_fileid_get**](docs/DefaultApi.md#accounts_account_id_portins_orderid_loas_fileid_get) | **GET** /accounts/{accountId}/portins/{orderid}/loas/{fileid} | 
*DefaultApi* | [**accounts_account_id_portins_orderid_loas_fileid_metadata_delete**](docs/DefaultApi.md#accounts_account_id_portins_orderid_loas_fileid_metadata_delete) | **DELETE** /accounts/{accountId}/portins/{orderid}/loas/{fileid}/metadata | 
*DefaultApi* | [**accounts_account_id_portins_orderid_loas_fileid_metadata_get**](docs/DefaultApi.md#accounts_account_id_portins_orderid_loas_fileid_metadata_get) | **GET** /accounts/{accountId}/portins/{orderid}/loas/{fileid}/metadata | 
*DefaultApi* | [**accounts_account_id_portins_orderid_loas_fileid_metadata_put**](docs/DefaultApi.md#accounts_account_id_portins_orderid_loas_fileid_metadata_put) | **PUT** /accounts/{accountId}/portins/{orderid}/loas/{fileid}/metadata | 
*DefaultApi* | [**accounts_account_id_portins_orderid_loas_fileid_put**](docs/DefaultApi.md#accounts_account_id_portins_orderid_loas_fileid_put) | **PUT** /accounts/{accountId}/portins/{orderid}/loas/{fileid} | 
*DefaultApi* | [**accounts_account_id_portins_orderid_loas_get**](docs/DefaultApi.md#accounts_account_id_portins_orderid_loas_get) | **GET** /accounts/{accountId}/portins/{orderid}/loas | 
*DefaultApi* | [**accounts_account_id_portins_orderid_loas_post**](docs/DefaultApi.md#accounts_account_id_portins_orderid_loas_post) | **POST** /accounts/{accountId}/portins/{orderid}/loas | 
*DefaultApi* | [**accounts_account_id_portins_orderid_notes_get**](docs/DefaultApi.md#accounts_account_id_portins_orderid_notes_get) | **GET** /accounts/{accountId}/portins/{orderid}/notes | 
*DefaultApi* | [**accounts_account_id_portins_orderid_notes_post**](docs/DefaultApi.md#accounts_account_id_portins_orderid_notes_post) | **POST** /accounts/{accountId}/portins/{orderid}/notes | 
*DefaultApi* | [**accounts_account_id_portins_orderid_npa_nxx_get**](docs/DefaultApi.md#accounts_account_id_portins_orderid_npa_nxx_get) | **GET** /accounts/{accountId}/portins/{orderid}/npaNxx | 
*DefaultApi* | [**accounts_account_id_portins_orderid_put**](docs/DefaultApi.md#accounts_account_id_portins_orderid_put) | **PUT** /accounts/{accountId}/portins/{orderid} | 
*DefaultApi* | [**accounts_account_id_portins_orderid_tns_get**](docs/DefaultApi.md#accounts_account_id_portins_orderid_tns_get) | **GET** /accounts/{accountId}/portins/{orderid}/tns | 
*DefaultApi* | [**accounts_account_id_portins_orderid_totals_get**](docs/DefaultApi.md#accounts_account_id_portins_orderid_totals_get) | **GET** /accounts/{accountId}/portins/{orderid}/totals | 
*DefaultApi* | [**accounts_account_id_portins_post**](docs/DefaultApi.md#accounts_account_id_portins_post) | **POST** /accounts/{accountId}/portins | 
*DefaultApi* | [**accounts_account_id_portins_totals_get**](docs/DefaultApi.md#accounts_account_id_portins_totals_get) | **GET** /accounts/{accountId}/portins/totals | 
*DefaultApi* | [**accounts_account_id_portouts_get**](docs/DefaultApi.md#accounts_account_id_portouts_get) | **GET** /accounts/{accountId}/portouts | 
*DefaultApi* | [**accounts_account_id_portouts_orderid_get**](docs/DefaultApi.md#accounts_account_id_portouts_orderid_get) | **GET** /accounts/{accountId}/portouts/{orderid} | 
*DefaultApi* | [**accounts_account_id_products_get**](docs/DefaultApi.md#accounts_account_id_products_get) | **GET** /accounts/{accountId}/products | 
*DefaultApi* | [**accounts_account_id_reports_get**](docs/DefaultApi.md#accounts_account_id_reports_get) | **GET** /accounts/{accountId}/reports | 
*DefaultApi* | [**accounts_account_id_reports_instances_get**](docs/DefaultApi.md#accounts_account_id_reports_instances_get) | **GET** /accounts/{accountId}/reports/instances | 
*DefaultApi* | [**accounts_account_id_reports_reportid_get**](docs/DefaultApi.md#accounts_account_id_reports_reportid_get) | **GET** /accounts/{accountId}/reports/{reportid} | 
*DefaultApi* | [**accounts_account_id_reports_reportid_instances_get**](docs/DefaultApi.md#accounts_account_id_reports_reportid_instances_get) | **GET** /accounts/{accountId}/reports/{reportid}/instances | 
*DefaultApi* | [**accounts_account_id_reports_reportid_instances_instance_id_file_get**](docs/DefaultApi.md#accounts_account_id_reports_reportid_instances_instance_id_file_get) | **GET** /accounts/{accountId}/reports/{reportid}/instances/{instanceId}/file | 
*DefaultApi* | [**accounts_account_id_reports_reportid_instances_instance_id_get**](docs/DefaultApi.md#accounts_account_id_reports_reportid_instances_instance_id_get) | **GET** /accounts/{accountId}/reports/{reportid}/instances/{instanceId} | 
*DefaultApi* | [**accounts_account_id_reports_reportid_instances_post**](docs/DefaultApi.md#accounts_account_id_reports_reportid_instances_post) | **POST** /accounts/{accountId}/reports/{reportid}/instances | 
*DefaultApi* | [**accounts_account_id_sipcredentials_get**](docs/DefaultApi.md#accounts_account_id_sipcredentials_get) | **GET** /accounts/{accountId}/sipcredentials | 
*DefaultApi* | [**accounts_account_id_sipcredentials_post**](docs/DefaultApi.md#accounts_account_id_sipcredentials_post) | **POST** /accounts/{accountId}/sipcredentials | 
*DefaultApi* | [**accounts_account_id_sipcredentials_user_name_delete**](docs/DefaultApi.md#accounts_account_id_sipcredentials_user_name_delete) | **DELETE** /accounts/{accountId}/sipcredentials/{userName} | 
*DefaultApi* | [**accounts_account_id_sipcredentials_user_name_get**](docs/DefaultApi.md#accounts_account_id_sipcredentials_user_name_get) | **GET** /accounts/{accountId}/sipcredentials/{userName} | 
*DefaultApi* | [**accounts_account_id_sipcredentials_user_name_put**](docs/DefaultApi.md#accounts_account_id_sipcredentials_user_name_put) | **PUT** /accounts/{accountId}/sipcredentials/{userName} | 
*DefaultApi* | [**accounts_account_id_sites_get**](docs/DefaultApi.md#accounts_account_id_sites_get) | **GET** /accounts/{accountId}/sites | 
*DefaultApi* | [**accounts_account_id_sites_post**](docs/DefaultApi.md#accounts_account_id_sites_post) | **POST** /accounts/{accountId}/sites | 
*DefaultApi* | [**accounts_account_id_sites_site_id_delete**](docs/DefaultApi.md#accounts_account_id_sites_site_id_delete) | **DELETE** /accounts/{accountId}/sites/{siteId} | 
*DefaultApi* | [**accounts_account_id_sites_site_id_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_get) | **GET** /accounts/{accountId}/sites/{siteId} | 
*DefaultApi* | [**accounts_account_id_sites_site_id_inservice_numbers_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_inservice_numbers_get) | **GET** /accounts/{accountId}/sites/{siteId}/inserviceNumbers | 
*DefaultApi* | [**accounts_account_id_sites_site_id_orders_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_orders_get) | **GET** /accounts/{accountId}/sites/{siteId}/orders | 
*DefaultApi* | [**accounts_account_id_sites_site_id_orders_orderid_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_orders_orderid_get) | **GET** /accounts/{accountId}/sites/{siteId}/orders/{orderid} | 
*DefaultApi* | [**accounts_account_id_sites_site_id_orders_orderid_tns_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_orders_orderid_tns_get) | **GET** /accounts/{accountId}/sites/{siteId}/orders/{orderid}/tns | 
*DefaultApi* | [**accounts_account_id_sites_site_id_portins_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_portins_get) | **GET** /accounts/{accountId}/sites/{siteId}/portins | 
*DefaultApi* | [**accounts_account_id_sites_site_id_put**](docs/DefaultApi.md#accounts_account_id_sites_site_id_put) | **PUT** /accounts/{accountId}/sites/{siteId} | 
*DefaultApi* | [**accounts_account_id_sites_site_id_sippeers_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_sippeers_get) | **GET** /accounts/{accountId}/sites/{siteId}/sippeers | 
*DefaultApi* | [**accounts_account_id_sites_site_id_sippeers_post**](docs/DefaultApi.md#accounts_account_id_sites_site_id_sippeers_post) | **POST** /accounts/{accountId}/sites/{siteId}/sippeers | 
*DefaultApi* | [**accounts_account_id_sites_site_id_sippeers_sippeer_id_delete**](docs/DefaultApi.md#accounts_account_id_sites_site_id_sippeers_sippeer_id_delete) | **DELETE** /accounts/{accountId}/sites/{siteId}/sippeers/{sippeerId} | 
*DefaultApi* | [**accounts_account_id_sites_site_id_sippeers_sippeer_id_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_sippeers_sippeer_id_get) | **GET** /accounts/{accountId}/sites/{siteId}/sippeers/{sippeerId} | 
*DefaultApi* | [**accounts_account_id_sites_site_id_sippeers_sippeer_id_movetns_post**](docs/DefaultApi.md#accounts_account_id_sites_site_id_sippeers_sippeer_id_movetns_post) | **POST** /accounts/{accountId}/sites/{siteId}/sippeers/{sippeerId}/movetns | 
*DefaultApi* | [**accounts_account_id_sites_site_id_sippeers_sippeer_id_put**](docs/DefaultApi.md#accounts_account_id_sites_site_id_sippeers_sippeer_id_put) | **PUT** /accounts/{accountId}/sites/{siteId}/sippeers/{sippeerId} | 
*DefaultApi* | [**accounts_account_id_sites_site_id_sippeers_sippeer_id_tns_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_sippeers_sippeer_id_tns_get) | **GET** /accounts/{accountId}/sites/{siteId}/sippeers/{sippeerId}/tns | 
*DefaultApi* | [**accounts_account_id_sites_site_id_sippeers_sippeer_id_tns_tn_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_sippeers_sippeer_id_tns_tn_get) | **GET** /accounts/{accountId}/sites/{siteId}/sippeers/{sippeerId}/tns/{tn} | 
*DefaultApi* | [**accounts_account_id_sites_site_id_sippeers_sippeer_id_tns_tn_put**](docs/DefaultApi.md#accounts_account_id_sites_site_id_sippeers_sippeer_id_tns_tn_put) | **PUT** /accounts/{accountId}/sites/{siteId}/sippeers/{sippeerId}/tns/{tn} | 
*DefaultApi* | [**accounts_account_id_sites_site_id_sippeers_sippeer_id_totaltns_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_sippeers_sippeer_id_totaltns_get) | **GET** /accounts/{accountId}/sites/{siteId}/sippeers/{sippeerId}/totaltns | 
*DefaultApi* | [**accounts_account_id_sites_site_id_totaltns_get**](docs/DefaultApi.md#accounts_account_id_sites_site_id_totaltns_get) | **GET** /accounts/{accountId}/sites/{siteId}/totaltns | 
*DefaultApi* | [**accounts_account_id_subscriptions_get**](docs/DefaultApi.md#accounts_account_id_subscriptions_get) | **GET** /accounts/{accountId}/subscriptions | 
*DefaultApi* | [**accounts_account_id_subscriptions_post**](docs/DefaultApi.md#accounts_account_id_subscriptions_post) | **POST** /accounts/{accountId}/subscriptions | 
*DefaultApi* | [**accounts_account_id_subscriptions_subscriptionid_delete**](docs/DefaultApi.md#accounts_account_id_subscriptions_subscriptionid_delete) | **DELETE** /accounts/{accountId}/subscriptions/{subscriptionid} | 
*DefaultApi* | [**accounts_account_id_subscriptions_subscriptionid_get**](docs/DefaultApi.md#accounts_account_id_subscriptions_subscriptionid_get) | **GET** /accounts/{accountId}/subscriptions/{subscriptionid} | 
*DefaultApi* | [**accounts_account_id_subscriptions_subscriptionid_put**](docs/DefaultApi.md#accounts_account_id_subscriptions_subscriptionid_put) | **PUT** /accounts/{accountId}/subscriptions/{subscriptionid} | 
*DefaultApi* | [**accounts_account_id_tnoptions_get**](docs/DefaultApi.md#accounts_account_id_tnoptions_get) | **GET** /accounts/{accountId}/tnoptions | 
*DefaultApi* | [**accounts_account_id_tnoptions_orderid_get**](docs/DefaultApi.md#accounts_account_id_tnoptions_orderid_get) | **GET** /accounts/{accountId}/tnoptions/{orderid} | 
*DefaultApi* | [**accounts_account_id_tnoptions_orderid_history_get**](docs/DefaultApi.md#accounts_account_id_tnoptions_orderid_history_get) | **GET** /accounts/{accountId}/tnoptions/{orderid}/history | 
*DefaultApi* | [**accounts_account_id_tnoptions_post**](docs/DefaultApi.md#accounts_account_id_tnoptions_post) | **POST** /accounts/{accountId}/tnoptions | 
*DefaultApi* | [**accounts_account_id_tnreservation_post**](docs/DefaultApi.md#accounts_account_id_tnreservation_post) | **POST** /accounts/{accountId}/tnreservation | 
*DefaultApi* | [**accounts_account_id_tnreservation_reservationid_delete**](docs/DefaultApi.md#accounts_account_id_tnreservation_reservationid_delete) | **DELETE** /accounts/{accountId}/tnreservation/{reservationid} | 
*DefaultApi* | [**accounts_account_id_tnreservation_reservationid_get**](docs/DefaultApi.md#accounts_account_id_tnreservation_reservationid_get) | **GET** /accounts/{accountId}/tnreservation/{reservationid} | 
*DefaultApi* | [**accounts_account_id_users_get**](docs/DefaultApi.md#accounts_account_id_users_get) | **GET** /accounts/{accountId}/users | 
*DefaultApi* | [**callbacks_notification_callback_api_post**](docs/DefaultApi.md#callbacks_notification_callback_api_post) | **POST** /callbacks/notificationCallbackApi | 
*DefaultApi* | [**callbacks_port_out_validation_callback_api_post**](docs/DefaultApi.md#callbacks_port_out_validation_callback_api_post) | **POST** /callbacks/portOutValidationCallbackApi | 
*DefaultApi* | [**cities_get**](docs/DefaultApi.md#cities_get) | **GET** /cities | 
*DefaultApi* | [**covered_rate_centers_get**](docs/DefaultApi.md#covered_rate_centers_get) | **GET** /coveredRateCenters | 
*DefaultApi* | [**covered_rate_centers_rate_center_id_get**](docs/DefaultApi.md#covered_rate_centers_rate_center_id_get) | **GET** /coveredRateCenters/{rateCenterId} | 
*DefaultApi* | [**rate_centers_get**](docs/DefaultApi.md#rate_centers_get) | **GET** /rateCenters | 
*DefaultApi* | [**tns_get**](docs/DefaultApi.md#tns_get) | **GET** /tns | 
*DefaultApi* | [**tns_tn_get**](docs/DefaultApi.md#tns_tn_get) | **GET** /tns/{tn} | 
*DefaultApi* | [**tns_tn_history_get**](docs/DefaultApi.md#tns_tn_history_get) | **GET** /tns/{tn}/history | 
*DefaultApi* | [**tns_tn_lata_get**](docs/DefaultApi.md#tns_tn_lata_get) | **GET** /tns/{tn}/lata | 
*DefaultApi* | [**tns_tn_lca_get**](docs/DefaultApi.md#tns_tn_lca_get) | **GET** /tns/{tn}/lca | 
*DefaultApi* | [**tns_tn_ratecenter_get**](docs/DefaultApi.md#tns_tn_ratecenter_get) | **GET** /tns/{tn}/ratecenter | 
*DefaultApi* | [**tns_tn_sippeers_get**](docs/DefaultApi.md#tns_tn_sippeers_get) | **GET** /tns/{tn}/sippeers | 
*DefaultApi* | [**tns_tn_sites_get**](docs/DefaultApi.md#tns_tn_sites_get) | **GET** /tns/{tn}/sites | 
*DefaultApi* | [**tns_tn_tndetails_get**](docs/DefaultApi.md#tns_tn_tndetails_get) | **GET** /tns/{tn}/tndetails | 
*DefaultApi* | [**tns_tn_tnreservation_get**](docs/DefaultApi.md#tns_tn_tnreservation_get) | **GET** /tns/{tn}/tnreservation | 
*DefaultApi* | [**users_userid_get**](docs/DefaultApi.md#users_userid_get) | **GET** /users/{userid} | 
*DefaultApi* | [**users_userid_password_put**](docs/DefaultApi.md#users_userid_password_put) | **PUT** /users/{userid}/password | 


## Documentation For Models



## Documentation For Authorization


## basic

- **Type**: HTTP basic authentication


## Author



