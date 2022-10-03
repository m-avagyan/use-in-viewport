## use-in-viewport

**React hook for check if the current element in viewport.**

**Author**

- name: _Martik Avagyan_
- email: _<martikavagyan1@gmail.com>_
- github: _[m-avagyan](https://github.com/m-avagyan)_

## Getting started

**Installation**

`npm install use-in-viewport` or `yarn add use-in-viewport`

**Example**

```javascript
import React, { useRef } from 'react';
import useInViewport from 'use-in-viewport';

function Example() {
  const elementRef = useRef(null);
  const inViewport = useInViewport(elementRef);

  return (
    <div ref={inViewport}>
      Element is {inViewport ? 'in viewport' : 'not in viewport'}
    </div>
  );
}

export default Example;
```

---

**Copyright (c) 2022 [Martik Avagyan](https://github.com/m-avagyan)**
