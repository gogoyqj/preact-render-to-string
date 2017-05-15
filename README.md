# qreact-render-to-string

qreact-render-to-string bases on [Jason Miller <jason@developit.ca> preact-render-to-string](https://github.com/developit/preact-render-to-string).

I make few changes so that it can work with [Qreact](https://github.com/gogoyqj/qreact).

# Usage

compatible with Original React.

```jsx
    import React from 'react';
    import { renderToString } from 'react-dom/server';
```

```jsx
    {
        alias: {
            'react-dom/server': 'qreact-render-to-string'
        }
    }
```

# Thanks to

[Jason Miller <jason@developit.ca>](https://github.com/developit).