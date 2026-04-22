<script setup>
import { themeColor } from "../data/items";
// import personPhoto from "../assets/images/person_1.jpg";
import mainPhoto from "/camera.jpg";

const service1Heading = "Services";
const service1SubHeading = "Our Core Services";
// const service1Quote =
//   '"At 4X Technologies, we provide cutting-edge solutions in security, safety, building management, and access control. Our services are designed to enhance the security, efficiency, and safety of your business and facilities, offering peace of mind with the most reliable systems available."';
// const personName = "James Anderson";
// const designation = "Facebook, Product Lead";
function youtubeVideoUrl() {
  const youtubeVideoId = "Q_p3pka81uc";
  return `https://www.youtube.com/embed/${youtubeVideoId}`;
}
</script>
<template>
  <div class="untree_co-section" id="features-section">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-4">
          <span
            class="caption"
            data-aos="fade-up"
            data-aos-delay="0"
            :style="[{ color: themeColor }]"
            >{{ service1Heading }}</span
          >
          <h3 class="heading mb-4" data-aos="fade-up" data-aos-delay="100">
            {{ service1SubHeading }}
          </h3>
          <div class="mb-4" data-aos="fade-up" data-aos-delay="200">
            <p>
              At 4X Technologies, we provide professional CCTV, PA system, and intercom solutions, including installation, configuration, maintenance, and system support. Our services are designed to improve security, communication, and operational efficiency for commercial, industrial, and residential properties.
            </p>
            <p>
              From surveillance systems and public address systems to intercom and integrated security solutions, our experienced team ensures every project is delivered with reliability, precision, and long-term performance.
            </p>
            <ul class="list-unstyled ul-check primary">
              <li>CCTV Installation & Configuration</li>
              <li>PA System Setup & Maintenance</li>
              <li>Intercom System Installation</li>
              <li>Security System Integration</li>
              <li>Preventive Maintenance & Troubleshooting</li>
              <li>After-Sales Support & Technical Assistance</li>
            </ul>
          </div>
          <div class="mb-4" data-aos="fade-up" data-aos-delay="400">
            <div class="untree_co-testimonial d-flex">
              <div class="text"></div>
            </div>
          </div>
        </div>
        <div class="col-lg-7 video" data-aos="fade-up" data-aos-delay="400">
          <a :href="youtubeVideoUrl()" class="btn-video" data-fancybox>
            <span class="wrap-icon-play">
              <svg
                class="bi bi-play-fill"
                width="1em"
                height="1em"
                viewBox="0 0 16 16"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M11.596 8.697l-6.363 3.692c-.54.313-1.233-.066-1.233-.697V4.308c0-.63.692-1.01 1.233-.696l6.363 3.692a.802.802 0 0 1 0 1.393z"
                />
              </svg>
            </span>
            <img :src="mainPhoto" alt="Image" class="img-fluid img-shadow" />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>
