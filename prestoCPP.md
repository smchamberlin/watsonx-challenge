# Provisioning a Presto (C++) engine
Last Updated: 2024-06-19
You can provision a Presto (C++) engine in IBM® watsonx.data to run SQL queries on your data source and fetch the queried data.

Supported by the following editions: watsonx.data Developer edition, watsonx.data on Red Hat® OpenShift®, watsonx.data SaaS on AWS

## Procedure
- Log in to the watsonx.data console.
- From the navigation menu, select Infrastructure Manager.
- To provision an engine, click Add component and select Add engine.
- In the Add engine window, provide the following details to sign up new compute to work with your data:
  - Field: Select the engine type (Presto (C++) v0.286) from the list.
  - Display name: Enter your compute engine name.
  - Size: Select the engine size. Custom size includes 1 coordinator node and 3 worker nodes.
  - Associated catalogs (optional): Associate the available catalogs (hive_data) with the engine if necessary.
Click Provision.

Content curated from:
https://www.ibm.com/docs/en/watsonx/watsonxdata/2.0.x
https://www.ibm.com/docs/en/watsonx/watsonxdata/2.0.x?topic=components-provisioning-presto-c-engine
