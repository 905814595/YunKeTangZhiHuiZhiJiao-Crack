# 使用指南

### example

```javascript
const ykt = require('YunkeTang');
ykt('user', 'pwd')
    .then(count => console.log(count))
    .catch(err => console.log(err));
```