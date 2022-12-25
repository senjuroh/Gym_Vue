<template>
  <div>
    <vs-card type="3">
      <template #title>
        <div style="font-size: 13px; color: var(--primary); font-weight: bold">
          {{ item.substring(0, 8) + "..." }}
        </div>
      </template>
      <template #img>
        <img
          :src="require(`../assets/products/${image}`)"
          alt=""
          width="150px"
          height="100px"
          style="object-fit: cover"
        />
      </template>
      <template #text>
        <p style="font-size: 12px">
          <del class="text-danger me-1">Rs.{{ price }} </del> <br />
          <b> Rs.{{ selling_price }}</b>
        </p>
        <p style="font-size: 11px">{{ vendor.substring(0, 10) + "..." }}</p>
      </template>
    </vs-card>
  </div>
</template>

<script>
export default {
  name: "OffercardComp",
  props: {
    item: null,
    price: null,
    selling_price: null,
    image: null,
    vendor: null,
  },
};
</script>

<style lang="scss" scoped>
</style>