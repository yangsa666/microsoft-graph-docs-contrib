---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestBody = new CheckMemberGroupsPostRequestBody();
$requestBody->setGroupIds(['f448435d-3ca7-4073-8152-a1fd73c0fd09', 'bd7c6263-4dd5-4ae8-8c96-556e1c0bece6', '93670da6-d731-4366-94b5-abed40b6016b', 'f5484ab1-4d4d-41ec-a9b8-754b3957bfc7', 'c9103f26-f3cf-4004-a611-2a14e81b8f79', 	]);



$result = $graphServiceClient->directoryObjects()->byDirectoryObjectId('directoryObject-id')->checkMemberGroups()->post($requestBody);


```