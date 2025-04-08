<script setup>
import mainPhoto from "/hero.jpg";
import { themeColor, siteName } from "../data/items";

const heroHeading = "Ensuring Safety and Security with Advanced Systems";
const buttonSeeFeature = "Explore Our Services";
const buttonContact = "Get in Touch";
</script>

<template>
  <div class="untree_co-hero" id="home-section">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-12">
          <div class="dots"></div>
          <div class="row align-items-center">
            <div
              class="col-lg-7 ml-auto order-lg-2"
              data-aos="fade-right"
              data-aos-delay="400"
            >
              <img
                :src="mainPhoto"
                alt="Hero Image"
                class="img-fluid rounded-border"
              />
            </div>
            <div class="col-lg-5">
              <h1 class="heading" data-aos="fade-up" data-aos-delay="0">
                {{ heroHeading }}
              </h1>
              <div class="excerpt" data-aos="fade-up" data-aos-delay="100">
                <p>
                  At
                  <span
                    style="
                      background-color: #ededed;
                      color: #404040;
                    "
                    >{{ siteName }}</span
                  >
                  , we specialize in installing state-of-the-art fire protection
                  and security alarm systems, safeguarding your premises with
                  reliability and precision
                </p>
              </div>
              <p data-aos="fade-up" data-aos-delay="200">
                <a
                  href="#features-section"
                  class="btn btn-primary smoothscroll service"
                  style="margin-right: 5px"
                  :style="[
                    { background: themeColor },
                    { borderColor: themeColor },
                  ]"
                  >{{ buttonSeeFeature }}</a
                >
                <a
                  href="#contact-section"
                  class="btn btn-outline-primary smoothscroll contact"
                  :style="[{ color: themeColor }, { borderColor: themeColor }]"
                  >{{ buttonContact }}</a
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.rounded-border {
  border-radius: 1%; /* This will make the image circular */
  border: 1px #fff; /* Adjust border thickness and color */
}
</style>
