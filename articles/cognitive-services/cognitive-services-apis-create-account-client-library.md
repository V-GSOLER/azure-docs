---
title: Create Cognitive Services resource using Azure Management client library
titleSuffix: Azure Cognitive Services
description: Create and manage Azure Cognitive Services resources using the Azure Management client library.
services: cognitive-services
keywords: cognitive services, cognitive intelligence, cognitive solutions, ai services
author: PatrickFarley
manager: nitinme
ms.service: cognitive-services
ms.topic: quickstart
ms.date: 06/04/2021
ms.author: pafarley
zone_pivot_groups: programming-languages-set-ten
ms.custom: mode-other
---

# Quickstart: Create a Cognitive Services resource using the Azure Management client library

Use this quickstart to create and manage Azure Cognitive Services resources using the Azure Management client library.

Azure Cognitive Services is a family of cloud-base services with REST APIs and client libraries available to help developers build cognitive intelligence into their applications. Developers do not need direct artificial intelligence (AI) or data science skills or knowledge to achieve success. Azure Cognitive Services enables developers to easily add cognitive features into their applications with cognitive solutions that can see, hear, speak, understand, and even begin to reason.

Individual AI services are represented by Azure [resources](../azure-resource-manager/management/manage-resources-portal.md) that you create under your Azure subscription. After you create a resource, you can use the keys and endpoint generated to authenticate your applications.

::: zone pivot="programming-language-csharp"

[!INCLUDE [C# SDK quickstart](includes/quickstarts/management-csharp.md)]

::: zone-end

::: zone pivot="programming-language-java"

[!INCLUDE [Java SDK quickstart](includes/quickstarts/management-java.md)]

::: zone-end

::: zone pivot="programming-language-javascript"

[!INCLUDE [NodeJS SDK quickstart](includes/quickstarts/management-node.md)]

::: zone-end

::: zone pivot="programming-language-python"

[!INCLUDE [Python SDK quickstart](includes/quickstarts/management-python.md)]

::: zone-end
