<script setup>
import { themeColor, contactInfo } from "../data/items";

const heading = "Get In Touch";
const subHeading = "Far from the countries Vokalia and Consonantia";
const contactInfoHeading = "Contact Information";
const buttonSendMessage = "Send Message";
const labels = {
  firstName: "First Name",
  lastName: "Last Name",
  email: "Email Address",
  message: "Message",
};
</script>

<template>
  <div class="untree_co-section" id="contact-section">
    <div class="container">
      <div class="row mb-4" data-aos="fade-up" data-aos-delay="0">
        <div class="col-12 text-center">
          <h2 class="heading">{{ heading }}</h2>
          <p>{{ subHeading }}</p>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-7">
          <form
            class="contact-form"
            data-aos="fade-up"
            data-aos-delay="100"
            action="https://formspree.io/f/mgvapqyd"
            method="POST"
          >
            <div class="row">
              <div class="col-6">
                <div class="form-group">
                  <label class="" for="fname">{{ labels.firstName }}</label>
                  <input
                    type="text"
                    class="form-control"
                    id="fname"
                    name="First Name"
                  />
                </div>
              </div>
              <div class="col-6">
                <div class="form-group">
                  <label class="" for="lname">{{ labels.lastName }}</label>
                  <input
                    type="text"
                    class="form-control"
                    id="lname"
                    name="Last Name"
                  />
                </div>
              </div>
            </div>
            <div class="form-group">
              <label class="" for="email">{{ labels.email }}</label>
              <input
                type="email"
                class="form-control"
                id="email"
                name="Email"
              />
            </div>
            <div class="form-group">
              <label class="" for="message">{{ labels.message }}</label>
              <textarea
                name="Message"
                class="form-control"
                id="message"
                cols="30"
                rows="5"
              ></textarea>
            </div>
            <button
              type="submit"
              class="btn btn-primary btn-black-hover"
              :style="[
                { backgroundColor: themeColor },
                { borderColor: themeColor },
              ]"
            >
              {{ buttonSendMessage }}
            </button>
          </form>
        </div>
        <div class="col-lg-4 ml-auto" data-aos="fade-up" data-aos-delay="200">
          <h3 class="h5 mb-4">{{ contactInfoHeading }}</h3>
          <address class="text-black d-flex">
            <span class="mt-1 icon-room mr-2"></span>
            <a
              :href="`https://www.google.com/maps/search/?api=1&query=${encodeURIComponent(
                contactInfo.address
              )}`"
              target="_blank"
              class="text-black"
              style="text-decoration: none"
            >
              {{ contactInfo.address }}
            </a>
          </address>
          <ul class="list-unstyled ul-links mb-4">
            <li>
              <a :href="'tel://' + contactInfo.phone1" class="d-flex"
                ><span class="mt-1 icon-phone mr-2"></span
                ><span>{{ contactInfo.phone1 }}</span></a
              >
            </li>

            <li>
              <a :href="'mailto:' + contactInfo.email" class="d-flex"
                ><span class="mt-1 icon-envelope mr-2"></span
                ><span>{{ contactInfo.email }}</span></a
              >
            </li>
            <li>
              <a :href="[contactInfo.website]" target="_blank" class="d-flex"
                ><span class="mt-1 icon-globe mr-2"></span
                ><span>{{ contactInfo.website }}</span></a
              >
            </li>
            <li>
              <a
                :href="'https://wa.me/' + [contactInfo.whatsapp]"
                target="_blank"
                class="d-flex"
                ><i class="fab fa-whatsapp mt-1 mr-2"></i
                ><span>WhatsApp Us</span></a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
button.btn-primary.btn-black-hover:hover {
  transform: scale(1.05);
}
address a:hover {
  color: #407bff;
  text-decoration: underline;
}
</style>
