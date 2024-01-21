# get-system-proxy

Get system proxy for macOS/Windows.

## Use

```js
import { get as getSystemProxy } from 'get-system-proxy'

getSystemProxy().then(proxy => {
  console.log(proxy) // ProxyInfo | undefined
})
```
