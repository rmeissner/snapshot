<template>
  <Block>
    <div class="d-flex flex-items-baseline">
      <h3 v-text="network.name" />
      <div v-text="network.key" class="ml-1 text-gray" />
    </div>
    <div class="text-gray">
      In {{ _n(network.spaces.length) }} space(s)
    </div>
  </Block>
</template>

<script>
export default {
  props: ['network']
};
</script>
