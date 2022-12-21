<template>
  <vs-card>
    <template #title>
      <h3 style="color: var(--primary)">{{ name }}</h3>
    </template>
    <template #img>
      <a href="" @click.prevent="$router.push({ name: '' })">
        <img
          :src="require(`../assets/gym/${image}`)"
          alt=""
          height="200px"
          width="220px"
        />
      </a>
    </template>
    <template #text>
      <p>
        {{ street }}, {{ city }},
        {{ country }}
      </p>
    </template>
  </vs-card>
</template>

<script>
export default {
  name: "CardComp",
  props: {
    name: null,
    image: null,
    street: null,
    city: null,
    country: null,
  },
};
</script>

<style lang="scss" scoped>
</style>