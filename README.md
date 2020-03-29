# vue-sreveal
Vue wrapper for [ScrollReveal](https://github.com/michelmany/vue-sreveal). Easy scroll animations for web and mobile browsers.

## Install

``` bash
# npm
npm install --save vue-sreveal
```

## Use

```javascript

import VueScrollReveal from 'vue-sreveal';

Vue.use(VueScrollReveal);
```

```html
<!-- In a component -->
<template>
  <main>
    <section v-scroll-reveal="{ delay: 2000 }">
      <h1>Hello World!</h1>
    </section>
  </main>
</template>

```