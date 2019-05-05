---
name: 'fc'
description: 'react functional component'
message: 'Please enter Component name.'
root: '.'
output: '**/*'
ignore: []
---

# `{{ input }}.tsx`

```tsx
import React from 'react';

type {{ input }}Props = {};

const {{ input }}: React.FC<{{ input }}Props> = props => <p>{{ input }} Component.</p>;

export default {{ input }}

```
