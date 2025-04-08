<script setup>
import { themeColor } from "../data/items";
import mainPhoto from "/about.jpg";

const heading = "About";
const subHeading = "About Us";
const totalMembers = "20";
const YearEts = "6";
</script>

<template>
  <div class="untree_co-section" id="about-section">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-8" data-aos="fade-up" data-aos-delay="100">
          <img :src="mainPhoto" alt="Image" class="img-fluid" />
        </div>
        <div class="col-lg-4">
          <div class="mb-4" data-aos="fade-up" data-aos-delay="0">
            <span class="caption" :style="[{ color: themeColor }]">{{
              heading
            }}</span>
            <h2 class="heading">{{ subHeading }}</h2>
          </div>
          <div class="mb-4" data-aos="fade-up" data-aos-delay="100">
            <p>
              Established in October 2018, 4X Technologies Pte. Ltd. is a
              Singapore-based company specializing in the installation of fire
              protection and security alarm systems. Our primary goal is to
              enhance safety and security for both residential and commercial
              clients across Singapore.​
            </p>
            <p>
              <span class="highlight">Our Commitment</span><br />
              Operating from our office at 3024 Ubi Road 3, #02-51, Kampong Ubi
              Industrial Estate, Singapore 408652, we are dedicated to
              delivering high-quality installations and exceptional customer
              service. Our experienced technicians work closely with clients to
              assess their specific requirements, ensuring that our solutions
              are both effective and aligned with their safety objectives.​
            </p>
          </div>
          <ul
            class="list-unstyled ul-check primary mb-4"
            data-aos="fade-up"
            data-aos-delay="200"
          >
            <li>Safety First, Always Protected</li>
            <li>Securing Your Future with Every Installation</li>
            <li>Trusted Solutions for a Safer Singapore</li>
          </ul>
          <div class="row count-numbers">
            <div class="col-lg-6" data-aos="fade-up" data-aos-delay="0">
              <span class="counter d-block"
                ><span :data-number="totalMembers">{{ totalMembers }}</span
                ><span></span
              ></span>
              <span class="caption-2">Members</span>
            </div>
            <div class="col-lg-6" data-aos="fade-up" data-aos-delay="100">
              <span class="counter d-block"
                ><span :data-number="YearEts">{{ YearEts }}</span
                ><span></span
              ></span>
              <span class="caption-2">Years</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
