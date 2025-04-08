<script setup>
import mainPhoto1 from "/Security & Surveillance Solutions.png";
import mainPhoto2 from "/Fire & Safety Systems.jpeg";
import mainPhoto3 from "/Building & Facility Management.jpg";
import mainPhoto4 from "/Access & Control Systems.jpg";

const items = [
  {
    id: 1,
    name: "Security & Surveillance Solutions",
    des: "Advanced CCTV, access control, intercom, and turnstile systems to ensure 24/7 security and efficient visitor management.",
  },
  {
    id: 2,
    name: "Fire & Safety Systems",
    des: "Design, installation, and maintenance of fire alarm systems and emergency toilet call systems for maximum safety.",
  },
  {
    id: 3,
    name: "Building & Facility Management",
    des: "Comprehensive solutions including elevator systems, AV setups, and reliable PA systems for smooth facility operations.",
  },
  {
    id: 4,
    name: "Access & Control Systems",
    des: "Secure entry and vehicle access with advanced car park barrier systems and access card solutions.",
  },
];
const total = 4;
</script>

<template>
  <div class="untree_co-section bg-light">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-5 order-lg-2 js-custom-dots">
          <a
            href="#"
            class="service link horizontal d-flex active"
            data-aos="fade-left"
            data-aos-delay="0"
          >
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
              <h3>{{ items[0].name }}</h3>
              <p>{{ items[0].des }}</p>
            </div>
          </a>
          <a
            href="#"
            class="service link horizontal d-flex"
            data-aos="fade-left"
            data-aos-delay="100"
          >
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
              <h3>{{ items[1].name }}</h3>
              <p>{{ items[1].des }}</p>
            </div>
          </a>
          <a
            href="#"
            class="service link horizontal d-flex"
            data-aos="fade-left"
            data-aos-delay="200"
          >
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
              <h3>{{ items[2].name }}</h3>
              <p>{{ items[2].des }}</p>
            </div>
          </a>
          <a
            href="#"
            class="service link horizontal d-flex"
            data-aos="fade-left"
            data-aos-delay="300"
          >
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
                  d="M9 17.25v1.007a3 3 0 0 1-.879 2.122L7.5 21h9l-.621-.621A3 3 0 0 1 15 18.257V17.25m6-12V15a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 15V5.25m18 0A2.25 2.25 0 0 0 18.75 3H5.25A2.25 2.25 0 0 0 3 5.25m18 0V12a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 12V5.25"
                />
              </svg>
            </div>
            <div class="service-contents">
              <h3>{{ items[3].name }}</h3>
              <p>{{ items[3].des }}</p>
            </div>
          </a>
        </div>
        <div class="col-lg-7">
          <div class="img-shadow">
            <div class="owl-single no-dots owl-carousel">
              <div class="item">
                <!-- page number -->
                <!-- <span class="number">{{ items[0].id }}/{{ total }}</span> -->
                <img :src="mainPhoto1" alt="Image" class="img-fluid" />
              </div>
              <div class="item">
                <!-- <span class="number">{{ items[1].id }}/{{ total }}</span> -->
                <img :src="mainPhoto2" alt="Image" class="img-fluid" />
              </div>
              <div class="item">
                <!-- <span class="number">{{ items[2].id }}/{{ total }}</span> -->
                <img :src="mainPhoto3" alt="Image" class="img-fluid" />
              </div>
              <div class="item">
                <!-- <span class="number">{{ items[3].id }}/{{ total }}</span> -->
                <img :src="mainPhoto4" alt="Image" class="img-fluid" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
