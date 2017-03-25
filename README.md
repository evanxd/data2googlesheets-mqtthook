# Data2GoogleSheets MQTThook
A MQTThook to store sensors data from an IoT device in a Google Sheets sheet.

## How-to
Initialize an Data2GoogleSheets MQTThook instance.
```js
var Data2GoogleSheetsMQTThook = require('data2googlesheets-mqtthook');
var hook = new Data2GoogleSheetsMQTThook();
```

Start to hook.
```js
hook.hook();
```

Stop to hook.
```js
hook.unhook();
```
