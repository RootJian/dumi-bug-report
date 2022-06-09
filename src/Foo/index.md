---
nav:
  title: Components
  path: /components
---

## Foo

Demo:

```tsx
import React from 'react';
import { usePrefersColor } from 'dumi/theme';

export default props => {
  const [color, setColor] = usePrefersColor();

  return (
    <>
      <button onClick={() => setColor('auto')}>启用自动主题色</button>
      当前主题色配置为：{color}
    </>
  );
};
```

More skills for writing demo: https://d.umijs.org/guide/basic#write-component-demo
