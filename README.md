# ip-handler
Module tools for writing, reading and handling ip addresses.

https://www.npmjs.com/package/ip-handler

# npm install

```javascript
npm install --save ip-handler
```

# Description
The ip-handler module allows you to write ip from integers and extract integers as well.
It also offers ip and ip-to-int modules operations.

https://www.npmjs.com/package/ip

https://www.npmjs.com/package/ip-to-int

# Usage

```javascript
const ipHandler = require('ip-handler');

let ip = ipHandler.ip(); //returns an ip object from ip module

ipHandler.writeIp(192,168,0,1);// '192.168.0.1'
ipHandler.readIp('192.168.0.1'); // [192, 168, 0, 1]

ipHandler.toInt('192.168.0.1'); // 3232235521
ipHandler.toIP(3232235521);// '192.168.0.1'

````
