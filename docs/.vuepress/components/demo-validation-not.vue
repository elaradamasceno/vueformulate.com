<template>
  <FormulateInput
    type="text"
    name="framework"
    label="What is your favorite javascript framework?"
    validation="not:jquery,ember,mootools"
    error-behavior="live"
    autocomplete="no"
  />
</template>

<script>
export default {

}
</script>

<style>

</style>
