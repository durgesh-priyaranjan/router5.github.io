# History plugin


The history plugin will automatically update your browser URL and state on route changes. It will also listen to popstate events (triggered
by back and forward buttons and manual URL changes).

This plugin uses HTML5 history API and therefore is not compatible with browsers which don't support it. Refer to [caniuse.com](http://caniuse.com/#search=history)
for browser compatibility.

```javascript
import historyPlugin from 'router5-history';

const router = new Router5()
    .usePlugin(historyPlugin())
    .start();
```

For more information on how to install, look at [Get started](/docs/get-started.html).
