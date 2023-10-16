---
title: "List messages"
description: "Get the messages in the signed-in user's mailbox (including the Deleted Items and Clutter folders)."
ms.localizationpriority: high
author: "SuryaLashmiS"
ms.prod: "outlook"
doc_type: apiPageType
dev_langs:
  - http
  - csharp
  - cli
  - go
  - java
  - javascript
  - php
  - powershell
  - python
---

```http
GET https://graph.microsoft.com/v1.0/me/messages?$select=sender,subject
```

```csharp
var foo = bar();
```

```bash
mgc-beta users messages list --user-id {user-id} --select "sender,subject"
```

```go
foo := bar()
```

```java
const fooJava = barJava();
```

```javascript
const fooJs = barJs();
```

```php
foo = barPhP();
```

```powershell
$foo = Get-Bar
```

```python
foo = get_bar()
```
