---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = SiteSource(
	site = Site(
		web_url = "https://m365x809305.sharepoint.com/sites/Retail",
	),
)

result = await graph_client.security.cases.ediscovery_cases.by_ediscovery_case_id('ediscoveryCase-id').custodians.by_custodian_id('ediscoveryCustodian-id').site_sources.post(request_body = request_body)


```