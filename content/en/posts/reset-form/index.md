---
title: How to reset a htlml form on submit using JavaScript
date: 2024-01-31
tags:
  - html-form
  - javascript
---

By default html forms are reset and all fields are cleared when we submit them.  
However, in instances whereby you use the `preventDefault()` method in the JavaScript file, the form doesn't reset automatically.  
In such situations we have to trigger the reset event manually using the following [JavaScript method](https://www.w3schools.com/jsref/met_form_reset.asp):

```JavaScript
document.getElementById("formId").reset();
```

### Links

https://www.w3schools.com/jsref/met_form_reset.asp
