# vue3 过渡笔记
#### **构建页面时的区别有哪些?**
需要从 `vue` 引入 `ref` 和 `reactive`。

::: tip
在使用 `vuex4.0` 时，需要使用 `import {userStore} from "vuex"` 来引入hook，再通过 `const store = useStore()` 来接收暴露的数据。
:::
#### **动态组件**
``` html
<script setup>
import Foo from './Foo.vue'
import Bar from './Bar.vue'
</script>

<template>
  <component :is="Foo" />
  <component :is="someCondition ? Foo : Bar" />
</template>

```

# 测试

#### 测试 
# vue3 过渡笔记
#### **构建页面时的区别有哪些?**
需要从 `vue` 引入 `ref` 和 `reactive`。

::: tip
在使用 `vuex4.0` 时，需要使用 `import {userStore} from "vuex"` 来引入hook，再通过 `const store = useStore()` 来接收暴露的数据。
:::
#### **动态组件**
``` html
<script setup>
import Foo from './Foo.vue'
import Bar from './Bar.vue'
</script>

<template>
  <component :is="Foo" />
  <component :is="someCondition ? Foo : Bar" />
</template>

```

# 测试

#### 测试 
# vue3 过渡笔记
#### **构建页面时的区别有哪些?**
需要从 `vue` 引入 `ref` 和 `reactive`。

::: tip
在使用 `vuex4.0` 时，需要使用 `import {userStore} from "vuex"` 来引入hook，再通过 `const store = useStore()` 来接收暴露的数据。
:::
#### **动态组件**
``` html
<script setup>
import Foo from './Foo.vue'
import Bar from './Bar.vue'
</script>

<template>
  <component :is="Foo" />
  <component :is="someCondition ? Foo : Bar" />
</template>

```

# 测试

#### 测试 
