<template>
  <div class="double-pane">
    <div class="pane">
      <FormulateInput
        v-model="value"
        type="radio"
        label="Label for radio items"
        :options="{first: 'First', second: 'Second', third: 'Third', fourth: 'Fourth'}"
      />
    </div>
    <code class="pane code">value: {{ value }}</code>
  </div>
</template>

<script>
export default {
  data () {
    return {
      value: 'second'
    }
  }
}
</script>
