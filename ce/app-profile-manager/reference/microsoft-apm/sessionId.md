---
title: "sessionId property (app profile manager) JavaScript API Reference | MicrosoftDocs"
description: "Learn about the sessionId property of app profile manager in Customer Service workspace."
author: mh-jaya
ms.author: v-jmh
manager: shujoshi
ms.date: 08/25/2021
ms.topic: reference
---

# Preview: sessionId (app profile manager)

[!include[cc-beta-prerelease-disclaimer](../../../includes/cc-beta-prerelease-disclaimer.md)]

The ID of a session.

## Syntax

`Microsoft.Apm.getSession(sessionId).focus();`

## Example

```JavaScript
const session = Microsoft.Apm.getFocusedSession();
console.log(session.sessionId);
```

[!INCLUDE[footer-include](../../../includes/footer-banner.md)]
