<script>
export default {
  props: {
    label: String,
    value: String
  }
};
</script>

<template>
  <div>
    <span style="font-weight: bold; font-size: 20px">{{label}}</span>
    <span>{{value}}</span>
  </div>
</template>
