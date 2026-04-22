<script setup>
import { themeColor } from "../data/items";
import mainPhoto from "/about.jpg";

const heading = "About";
const subHeading = "About Us";
const totalMembers = "30";
const YearEts = "7";
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
              Established in October 2018, 4X Technologies Pte. Ltd. is a Singapore-based company specializing in CCTV, PA systems, intercom systems, and integrated security solutions. We provide professional installation, configuration, maintenance, and system support for commercial, industrial, and residential projects across Singapore.

Our mission is to deliver reliable security, clear communication, and smart system integration that help businesses and property owners create safer and more efficient environments.
            </p>
            <p>
              <span class="highlight">Our Commitment</span><br />
              Based at 3024 Ubi Road 3, #02-51, Kampong Ubi Industrial Estate, Singapore 408652, we are committed to delivering quality workmanship, reliable service, and cost-effective security solutions. Our experienced team works closely with clients to provide trusted CCTV, PA, and intercom systems tailored to every project.</p>
          </div>
          <ul
            class="list-unstyled ul-check primary mb-4"
            data-aos="fade-up"
            data-aos-delay="200"
          >
            <li>Professional CCTV, PA & Intercom Solutions</li>
            <li>Securing Your Future with Every Installation</li>
            <li>Smart Security, Trusted Protection</li>
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
