# regEXTREME

Every RegExp you ever wanted but were afraid to ask for.

```bash
npm install --save regextreme
```

```javascript
var regextreme = require("regextreme");

regextreme.url.test("http://slashdot.org");
regextreme.objectId.test("56a14e5c3c87ad3007004b9f");
regextreme.email.test("stan@eminemsbiggestfan.com");
regextreme.ipv4.test("127.0.0.1");
regextreme.ipv6.test("0:0:0:0:0:0:0:1");

```

## Built in

- url (https://www.w3.org/TR/url-1/)
- objectId (https://docs.mongodb.com/manual/reference/method/ObjectId/)
- email (https://tools.ietf.org/html/rfc2822#section-3.4)
- ipv4
- ipv6
