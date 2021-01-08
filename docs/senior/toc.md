# Toc

<ClientOnly>
  <toc-nav />
</ClientOnly>

## Related configuration

Configure the titles included when generating directory navigation. The default is [2, 3].

```vue
<template>
  <v-md-editor :include-level="[3, 4]"></v-md-editor>
</template>
```

Configure toc to generate the title included in the navigation, the default value is [2, 3].

```js
VMdEditor.use(githubTheme, {
  config: {
    toc: {
      includeLevel: [3, 4],
    },
  },
});
```
