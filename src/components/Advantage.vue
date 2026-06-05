<script setup>
import { themeColor } from "../data/items";
const heading = "Advantage of using our services";
const subHeading = "Expert Fire & Safety Systems";
const buttonLearnMore = "Learn More";
const advantages = [
  {
    name: "Comprehensive Security & Surveillance Solutions",
    des: "We offer a complete range of advanced security systems, including CCTV, access control, intercom, and turnstile systems, providing robust protection for your premises 24/7.",
  },
  {
    name: "Expert Fire & Safety Systems",
    des: "Our specialized fire alarm systems and emergency toilet call systems ensure the safety of your property, with professional design, installation, and maintenance services.",
  },
  {
    name: "Seamless Building & Facility Management",
    des: "We provide integrated solutions for building operations, including elevator systems, AV setups, and PA systems, designed to enhance the efficiency and functionality of your facility.",
  },
  {
    name: "Reliable After-Sales Support & Maintenance",
    des: "With our 24/7 technical support and tailored maintenance packages, you can trust that your systems will always be in top working condition, minimizing downtime and enhancing operational reliability.",
  },
];
</script>

<template>
  <div class="untree_co-section">
    <div class="container">
      <div class="row mb-4">
        <div class="col-12 text-center" data-aos="fade-up" data-aos-delay="0">
          <h2 class="heading">{{ heading }}</h2>
          <p>{{ subHeading }}</p>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-6 mb-4" data-aos="fade-up" data-aos-delay="100">
          <div class="service horizontal d-flex">
            <div class="service-icon color-1 mb-4">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="size-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M16.5 10.5V6.75a4.5 4.5 0 1 0-9 0v3.75m-.75 11.25h10.5a2.25 2.25 0 0 0 2.25-2.25v-6.75a2.25 2.25 0 0 0-2.25-2.25H6.75a2.25 2.25 0 0 0-2.25 2.25v6.75a2.25 2.25 0 0 0 2.25 2.25Z"
                />
              </svg>
            </div>
            <div class="service-contents">
              <h3>{{ advantages[0].name }}</h3>
              <p>{{ advantages[0].des }}</p>
              <p>
                <a
                  href="#contact-section"
                  class="read-more"
                  :style="[{ color: themeColor }]"
                  >{{ buttonLearnMore }}</a
                >
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-6 mb-4" data-aos="fade-up" data-aos-delay="200">
          <div class="service horizontal d-flex">
            <div class="service-icon color-2 mb-4">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="size-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M15.362 5.214A8.252 8.252 0 0 1 12 21 8.25 8.25 0 0 1 6.038 7.047 8.287 8.287 0 0 0 9 9.601a8.983 8.983 0 0 1 3.361-6.867 8.21 8.21 0 0 0 3 2.48Z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M12 18a3.75 3.75 0 0 0 .495-7.468 5.99 5.99 0 0 0-1.925 3.547 5.975 5.975 0 0 1-2.133-1.001A3.75 3.75 0 0 0 12 18Z"
                />
              </svg>
            </div>
            <div class="service-contents">
              <h3>{{ advantages[1].name }}</h3>
              <p>{{ advantages[1].des }}</p>
              <p>
                <a
                  href="#contact-section"
                  class="read-more"
                  :style="[{ color: themeColor }]"
                  >{{ buttonLearnMore }}</a
                >
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-6 mb-4" data-aos="fade-up" data-aos-delay="300">
          <div class="service horizontal d-flex">
            <div class="service-icon color-3 mb-4">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="size-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Z"
                />
              </svg>
            </div>
            <div class="service-contents">
              <h3>{{ advantages[2].name }}</h3>
              <p>{{ advantages[2].des }}</p>
              <p>
                <a
                  href="#contact-section"
                  class="read-more"
                  :style="[{ color: themeColor }]"
                  >{{ buttonLearnMore }}</a
                >
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-6 mb-4" data-aos="fade-up" data-aos-delay="400">
          <div class="service horizontal d-flex">
            <div class="service-icon color-4 mb-4">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="size-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M20.25 8.511c.884.284 1.5 1.128 1.5 2.097v4.286c0 1.136-.847 2.1-1.98 2.193-.34.027-.68.052-1.02.072v3.091l-3-3c-1.354 0-2.694-.055-4.02-.163a2.115 2.115 0 0 1-.825-.242m9.345-8.334a2.126 2.126 0 0 0-.476-.095 48.64 48.64 0 0 0-8.048 0c-1.131.094-1.976 1.057-1.976 2.192v4.286c0 .837.46 1.58 1.155 1.951m9.345-8.334V6.637c0-1.621-1.152-3.026-2.76-3.235A48.455 48.455 0 0 0 11.25 3c-2.115 0-4.198.137-6.24.402-1.608.209-2.76 1.614-2.76 3.235v6.226c0 1.621 1.152 3.026 2.76 3.235.577.075 1.157.14 1.74.194V21l4.155-4.155"
                />
              </svg>
            </div>
            <div class="service-contents">
              <h3>{{ advantages[3].name }}</h3>
              <p>{{ advantages[3].des }}</p>
              <p>
                <a
                  href="#contact-section"
                  class="read-more"
                  :style="[{ color: themeColor }]"
                  >{{ buttonLearnMore }}</a
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
