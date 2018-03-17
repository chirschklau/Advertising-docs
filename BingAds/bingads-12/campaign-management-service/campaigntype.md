---
title: CampaignType Value Set - Campaign Management
ms.service: bing-ads-campaign-management-service
ms.topic: article
author: eric-urban
ms.author: eur
description: Defines the possible campaign types.
---
> [!IMPORTANT]
> This Bing Ads API Version 12 preview documentation is subject to change. To return to version 11 content, use the version selector near the table of contents at the top and left side of the page.

# CampaignType Value Set - Campaign Management
Defines the possible campaign types.

## Syntax
```xml
<xs:simpleType name="CampaignType" xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:list>
    <xs:simpleType>
      <xs:restriction base="xs:string">
        <xs:enumeration value="SearchAndContent" />
        <xs:enumeration value="Shopping" />
        <xs:enumeration value="DynamicSearchAds" />
        <xs:enumeration value="Audience" />
      </xs:restriction>
    </xs:simpleType>
  </xs:list>
</xs:simpleType>
```

## <a name="values"></a>Values

|Value|Description|
|-----------|---------------|
|<a name="audience"></a>Audience|Reserved.|
|<a name="dynamicsearchads"></a>DynamicSearchAds|The campaign is a Dynamic Search Ads campaign.|
|<a name="searchandcontent"></a>SearchAndContent|The campaign is a Search and Content campaign.|
|<a name="shopping"></a>Shopping|The campaign is a Bing Shopping campaign.|

## Requirements
Service: [CampaignManagementService.svc v12](https://campaign.api.bingads.microsoft.com/Api/Advertiser/CampaignManagement/v12/CampaignManagementService.svc)  
Namespace: https\://bingads.microsoft.com/CampaignManagement/v12  

## Used By
[Campaign](campaign.md)  
[GetCampaignsByAccountId](getcampaignsbyaccountid.md)  
[GetCampaignsByIds](getcampaignsbyids.md)  