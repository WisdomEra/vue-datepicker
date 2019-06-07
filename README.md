# Datepicker

Datepicker component is based on [flatpickr](https://github.com/chmln/flatpickr) and [vue-bulma-datepicker](https://github.com/vue-bulma/datepicker) for VueJs.

## Installation

```
$ npm install wisdom-vue-datepicker --save
```

## Examples

### Single Input

```vue
<template>
  <datepicker placeholder="European Format ('d-m-Y')" :config="{ dateFormat: 'd-m-Y', static: true }"></datepicker>
</template>

<script>
import Datepicker from 'wisdom-vue-datepicker'

export default {
  components: {
    Datepicker
  }
}
</script>
```

### Wrap Input

```vue
<template>
  <datepicker :config="{ wrap: true }" readonly>
    <a class="button" data-toggle><i class="fa fa-calendar"></i></a>
    <a class="button" data-clear><i class="fa fa-close"></i></a>
  </datepicker>
</template>

<script>
import Datepicker from 'wisdom-vue-datepicker'

export default {
  components: {
    Datepicker
  }
}
</script>
```

## Badges

![](https://img.shields.io/badge/license-GPL-blue.svg)
![](https://img.shields.io/badge/status-stable-green.svg)
