<script setup>
const items = [
  {
    
    title: "24/7 Monitoring & Support",
    description:
      "We provide around-the-clock monitoring and technical support, ensuring that your security and safety systems are always operational and ready when you need them.",
  },
  {
    
    title: "Customizable Solutions",
    description:
      "Our systems are tailored to meet the unique needs of each client, offering flexibility and scalability to adapt to various facility sizes and business requirements.",
  },
  {
    
    title: "Seamless Integration",
    description:
      "Our advanced security, fire safety, and building management systems are designed for easy integration, ensuring smooth operation and minimal disruption to your existing infrastructure.",
  },
  {
    
    title: "Cutting-Edge Technology",
    description:
      "We use the latest technology in CCTV, access control, fire alarm, and building management systems, ensuring that your premises are equipped with the most reliable and advanced solutions available.",
  },
];
</script>
<template>
  <div class="untree_co-section">
    <div class="container">
      <div class="row">
        <div
          class="col-md-6 mb-4 mb-lg-0 col-lg-3"
          data-aos="fade-up"
          data-aos-delay="0"
        >
          <div class="service">
            <div class="service-icon color-1 mb-4" :style="[items[0].iconBg]">
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
                  d="M8.625 9.75a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0H8.25m4.125 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0H12m4.125 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0h-.375m-13.5 3.01c0 1.6 1.123 2.994 2.707 3.227 1.087.16 2.185.283 3.293.369V21l4.184-4.183a1.14 1.14 0 0 1 .778-.332 48.294 48.294 0 0 0 5.83-.498c1.585-.233 2.708-1.626 2.708-3.228V6.741c0-1.602-1.123-2.995-2.707-3.228A48.394 48.394 0 0 0 12 3c-2.392 0-4.744.175-7.043.513C3.373 3.746 2.25 5.14 2.25 6.741v6.018Z"
                />
              </svg>
            </div>
            <div class="service-contents">
              <h3>{{ items[0].title }}</h3>
              <p>{{ items[0].description }}</p>
            </div>
          </div>
        </div>
        <div
          class="col-md-6 mb-4 mb-lg-0 col-lg-3"
          data-aos="fade-up"
          data-aos-delay="100"
        >
          <div class="service">
            <div class="service-icon color-2 mb-4" :style="[items[1].iconBg]">
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
                  d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m5.231 13.481L15 17.25m-4.5-15H5.625c-.621 0-1.125.504-1.125 1.125v16.5c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Zm3.75 11.625a2.625 2.625 0 1 1-5.25 0 2.625 2.625 0 0 1 5.25 0Z"
                />
              </svg>
            </div>
            <div class="service-contents">
              <h3>{{ items[1].title }}</h3>
              <p>{{ items[1].description }}</p>
            </div>
          </div>
        </div>
        <div
          class="col-md-6 mb-4 mb-lg-0 col-lg-3"
          data-aos="fade-up"
          data-aos-delay="200"
        >
          <div class="service">
            <div class="service-icon color-3 mb-4" :style="[items[2].iconBg]">
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
              <h3>{{ items[2].title }}</h3>
              <p>{{ items[2].description }}</p>
            </div>
          </div>
        </div>
        <div
          class="col-md-6 mb-4 mb-lg-0 col-lg-3"
          data-aos="fade-up"
          data-aos-delay="300"
        >
          <div class="service">
            <div class="service-icon color-4 mb-4" :style="[items[3].iconBg]">
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
              <h3>{{ items[3].title }}</h3>
              <p>{{ items[3].description }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
