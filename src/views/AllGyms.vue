<template>
  <template-view>
    <!-- Registerd Fitness Centers -->
    <section class="py-5 bg-light">
      <div class="container">
        <div class="row g-4">
          <div class="col-md-3">
            <card-comp
              name="Dharan Fitness Center"
              city="Dharan"
              country="Nepal"
              street="Bhote Pool"
              image="gym5.webp"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Rohan Fitness Center"
              city="Ithari"
              country="Nepal"
              street="Kalyan Chowk"
              image="gym1.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Crunch Fitness"
              city="Biratnagar"
              country="Nepal"
              street="Hari Marga"
              image="gym2.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="All Time Fitness"
              city="Dharan"
              country="Nepal"
              street="Kirat Chowk"
              image="gym3.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Miteri Gym & Zumba"
              city="Tarahara"
              country="Nepal"
              street="Hums"
              image="gym4.png"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Budhasubba Gym & Futsall"
              city="Dharan"
              country="Nepal"
              street="Hariyali"
              image="gym2.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Gorkhali Gym"
              city="Dharan"
              country="Nepal"
              street="Bhote Pool"
              image="gym1.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Rohan Fitness Center"
              city="Dharan"
              country="Nepal"
              street="Bhanu Chowk"
              image="gym5.webp"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Budhasubba Gym & Futsall"
              city="Ithari"
              country="Nepal"
              street="Balgram Chowk"
              image="gym3.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Miteri Gym & Zumba"
              city="Inarwa"
              country="Nepal"
              street="Shyam Chowk"
              image="gym4.png"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Crunch Fitness"
              city="Dharan"
              country="Nepal"
              street="Purano Bazzar"
              image="gym5.webp"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Budhasubba Gym & Futsall"
              city="Dharan"
              country="Nepal"
              street="Bhote Pool"
              image="gym1.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Dharan Fitness Center"
              city="Biratnagar"
              country="Nepal"
              street="Ram Marga"
              image="gym2.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Rohan Fitness Center"
              city="Tarahara"
              country="Nepal"
              street="Ganga Marga"
              image="gym4.png"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Budhasubba Gym & Futsall"
              city="Birat Chowk"
              country="Nepal"
              street="Sita Line"
              image="gym3.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Crunch Fitness"
              city="Dharan"
              country="Nepal"
              street="Bhote Pool"
              image="gym2.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Miteri Gym & Zumba"
              city="Ithari"
              country="Nepal"
              street="Halgada"
              image="gym1.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Budhasubba Gym & Futsall"
              city="Vedetar"
              country="Nepal"
              street="Sital Tol"
              image="gym5.webp"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Rohan Fitness Center"
              city="Biratnagar"
              country="Nepal"
              street="Rohan Line"
              image="gym4.png"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Budhasubba Gym & Futsall"
              city="Dharan"
              country="Nepal"
              street="Kirat Chowk"
              image="gym3.jpg"
            />
          </div>
        </div>
      </div>
    </section>
  </template-view>
</template>

<script>
import CardComp from "@/components/CardComp.vue";
import TemplateView from "./TemplateView.vue";
export default {
  components: {
    TemplateView,
    CardComp,
  },
  name: "AllVendors",
};
</script>

<style lang="scss" scoped>
</style>