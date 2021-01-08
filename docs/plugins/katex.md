# Katex

<ClientOnly>
  <plugin-katex />
</ClientOnly>

### Introduce katex resources from cdn

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/katex.min.css" />
<script src="https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/katex.min.js"></script>
```

### Import Plugin：

```js
import VueMarkdownEditor from '@kangc/v-md-editor';
import createKatexPlugin from '@kangc/v-md-editor/lib/plugins/katex/cdn';

VueMarkdownEditor.use(createKatexPlugin());
```

### Usage：

```vue
<template>
  <v-md-editor v-model="text" height="500px" />
</template>

<script>
export default {
  data() {
    return {
      text: '$$sum_{i=1}^n a_i=0$$',
    };
  },
};
</script>
```
