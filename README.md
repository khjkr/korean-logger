# korean-logger
> Korean Logger Modules

### Author
- khjkr (<khj@zeonplex.co.kr>) (KHJ#5137)

### License
- MIT

#### Special Thanks
- ZEONPLEX

### Installation
```
npm install korean-logger
```

## Examples
```js
const klog = require('korean-logger')

klog.log('text') // Result: [시간] [로그] text
klog.info('text') // Result: [시간] [정보] text
klog.success('text') // Result: [시간] [성공] text
klog.alert('text') // Result: [시간] [알림] text
klog.warn('text') // Result: [시간] [경고] text
klog.error('text') // Result: [시간] [오류] text
klog.chat('text') // Result: [시간] [채팅] text
klog.status('text') // Result: [시간] [상태] text
klog.debug('text') // Result: [시간] [디버그] text
```
