<template>
  <input class="input" :class="inputClass" type="text" :placeholder="placeholder" :readonly="readonly" :value="value"/>
</template>

<script>
export default {
  props: {
    alignment: String,
    config: {
      type: Object,
      default: () => ({})
    },
    l10n: {
      type: Object,
      default: () => ({})
    },
    placeholder: {
      type: String,
      default: 'Pick date'
    },
    readonly: Boolean,
    inputClass: {
      type: Object,
      default: () => ({})
    },
    value: {
      type: String,
      default: null
    }
  },

  data () {
    return {
    }
  }
}
</script>
