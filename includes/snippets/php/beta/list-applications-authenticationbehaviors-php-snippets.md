---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestConfiguration = new ApplicationsRequestBuilderGetRequestConfiguration();
$queryParameters = ApplicationsRequestBuilderGetRequestConfiguration::createQueryParameters();
$queryParameters->select = ["id","displayName","appId","authenticationBehaviors"];
$requestConfiguration->queryParameters = $queryParameters;


$result = $graphServiceClient->applications()->get($requestConfiguration);


```