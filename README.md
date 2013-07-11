IpInfoDb
========

An API wrapper for the IpInfoDb API

##Usage
```javascript
var IpAPI = require('ipinfodb').IpAPI;
var api = new IpAPI('api key',{url: 'http://api.ipinfodb.com/v3/ip-city/'});
var result = api.lookup('74.83.60.249')
```
