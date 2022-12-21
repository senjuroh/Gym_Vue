<template>
  <template-view>
    <section class="border-bottom py-5">
      <div class="container">
        <div class="row g-3">
          <div class="d-flex justify-content-between text-align-center mb-4">
            <div>
              <div class="head2">Featured Fitness Centers</div>
              <p class="text-muted">The nearest gyms to your location</p>
            </div>
            <div>
              <a href="#" @click.prevent="$router.push({ name: '' })">
                View all <i class="fa-solid fa-arrow-right"></i
              ></a>
            </div>
          </div>
          <div class="col-md-3">
            <card-comp
              name="Rohan"
              city="Dharan"
              country="Nepal"
              street="kalyan Chowk"
              image="gym1.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Rohan"
              city="Dharan"
              country="Nepal"
              street="kalyan Chowk"
              image="gym2.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Rohan"
              city="Dharan"
              country="Nepal"
              street="kalyan Chowk"
              image="gym3.jpg"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Rohan"
              city="Dharan"
              country="Nepal"
              street="kalyan Chowk"
              image="gym4.png"
            />
          </div>
          <!-- <div class="col-md-3">
            <card-comp
              name="Rohan"
              city="Dharan"
              country="Nepal"
              street="kalyan Chowk"
              image="gym5.webp"
            />
          </div>
          <div class="col-md-3">
            <card-comp
              name="Rohan"
              city="Dharan"
              country="Nepal"
              street="kalyan Chowk"
              image="gym1.jpg"
            />
          </div> -->
        </div>
      </div>
    </section>
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
