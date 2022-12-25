<template>
  <template-view>
    <section class="py-5">
      <div class="container">
        <div class="row g-3">
          <div class="col-md-3">
            <offercard-comp
              item="Dumbbell"
              price="3,000"
              selling_price=" 2,500"
              image="6.jpg"
              vendor="Senju Crossfits"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Barbell"
              price="7,500"
              selling_price=" 6,800"
              image="1.jpg"
              vendor="Rohan Fitness Center"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Barbell Stand"
              price="17,000"
              selling_price=" 15,600"
              image="2.jpg"
              vendor="Crunch Fitness"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Dumnbells"
              price="12,000"
              selling_price=" 11,250"
              image="5.jpg"
              vendor="Miteri Gym"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Shaker"
              price="1,000"
              selling_price="750"
              image="3.jpg"
              vendor="Senju Crossfits"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Medicinal Balls"
              price="12,800"
              selling_price="11,650"
              image="10.jpg"
              vendor="Rohan Gym"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Bottle"
              price="700"
              selling_price=" 650"
              image="4.jpg"
              vendor="Dharan Fitness Center"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Whey Protein"
              price="12,000"
              selling_price=" 11,500"
              image="12.jpg"
              vendor="All Time Fitness"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Barbell Plates"
              price="3,000"
              selling_price=" 2,600"
              image="11.jpg"
              vendor="Senju Crossfits"
            />
          </div>

          <div class="col-md-3">
            <offercard-comp
              item="Kettlebell"
              price="5,000"
              selling_price=" 4,700"
              image="8.jpg"
              vendor="Crunch Fitness"
            />
          </div>

          <div class="col-md-3">
            <offercard-comp
              item="Handgrip"
              price="1,200"
              selling_price=" 9,50"
              image="7.jpg"
              vendor="Senju Crossfits"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Medicinal Ball"
              price="3,200"
              selling_price=" 2,750"
              image="9.jpg"
              vendor="All Time Fitness"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Dumbbell"
              price="3,000"
              selling_price=" 2,500"
              image="6.jpg"
              vendor="Senju Crossfits"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Barbell"
              price="7,500"
              selling_price=" 6,800"
              image="1.jpg"
              vendor="Rohan Fitness Center"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Barbell Stand"
              price="17,000"
              selling_price=" 15,600"
              image="2.jpg"
              vendor="Crunch Fitness"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Dumnbells"
              price="12,000"
              selling_price=" 11,250"
              image="5.jpg"
              vendor="Miteri Gym"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Shaker"
              price="1,000"
              selling_price="750"
              image="3.jpg"
              vendor="Senju Crossfits"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Medicinal Balls"
              price="12,800"
              selling_price="11,650"
              image="10.jpg"
              vendor="Rohan Gym"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Bottle"
              price="700"
              selling_price=" 650"
              image="4.jpg"
              vendor="Dharan Fitness Center"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Whey Protein"
              price="12,000"
              selling_price=" 11,500"
              image="12.jpg"
              vendor="All Time Fitness"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Barbell Plates"
              price="3,000"
              selling_price=" 2,600"
              image="11.jpg"
              vendor="Senju Crossfits"
            />
          </div>

          <div class="col-md-3">
            <offercard-comp
              item="Kettlebell"
              price="5,000"
              selling_price=" 4,700"
              image="8.jpg"
              vendor="Crunch Fitness"
            />
          </div>

          <div class="col-md-3">
            <offercard-comp
              item="Handgrip"
              price="1,200"
              selling_price=" 9,50"
              image="7.jpg"
              vendor="Senju Crossfits"
            />
          </div>
          <div class="col-md-3">
            <offercard-comp
              item="Medicinal Ball"
              price="3,200"
              selling_price=" 2,750"
              image="9.jpg"
              vendor="All Time Fitness"
            />
          </div>
        </div>
      </div>
    </section>
  </template-view>
</template>

<script>
import TemplateView from "./TemplateView.vue";
import OffercardComp from "@/components/OffercardComp.vue";
export default {
  components: {
    TemplateView,
    OffercardComp,
  },
};
</script>

<style lang="scss" scoped>
</style>