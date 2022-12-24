<template>
  <template-view>
    <!-- Featured GYMs Section -->
    <section class="border-bottom py-5">
      <div class="container">
        <div class="row g-3">
          <div class="d-flex justify-content-between text-align-center mb-2">
            <div>
              <div class="head2">Featured Fitness Centers</div>
              <p class="text-muted">The nearest gyms to your location</p>
            </div>
            <div>
              <a href="#" @click.prevent="$router.push({ name: 'gym' })">
                View all <i class="fa-solid fa-arrow-right"></i
              ></a>
            </div>
          </div>
          <div class="col-md-3">
            <a href="#" @click.prevent="$router.push({ name: 'gym' })">
              <card-comp
                name="Dharan Fitness Center"
                city="Dharan"
                country="Nepal"
                street="Bhote Pool"
                image="gym1.jpg"
              />
            </a>
          </div>
          <div class="col-md-3">
            <a href="#" @click.prevent="$router.push({ name: 'gym' })">
              <card-comp
                name="Miteri Gym & Jumba"
                city="Dharan"
                country="Nepal"
                street="Bhanu Chowk"
                image="gym2.jpg"
              />
            </a>
          </div>
          <div class="col-md-3">
            <a href="#" @click.prevent="$router.push({ name: 'gym' })">
              <card-comp
                name="Rohan Fitness Center"
                city="Dharan"
                country="Nepal"
                street="Sayapatri Chowk"
                image="gym3.jpg"
              />
            </a>
          </div>
          <div class="col-md-3">
            <a href="" @click.prevent="$router.push({ name: 'gym' })">
              <card-comp
                name="Senju Crossfits"
                city="Dharan"
                country="Nepal"
                street="kalyan Chowk"
                image="gym4.png"
              />
            </a>
          </div>
        </div>
      </div>
    </section>
    <!-- About-Us Section-->
  </template-view>
</template>

<script>
import CardComp from "@/components/CardComp.vue";
import TemplateView from "./TemplateView.vue";
export default {
  name: "HomeView",
  components: {
    TemplateView,
    CardComp,
  },
};
</script>


<style>
</style>
