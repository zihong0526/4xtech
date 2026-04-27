<script setup>
import { contactInfo } from "../data/items";

const copyrightText = "Copyright 2025, All rights reserved.";
const column1Heading = "About 4x Technologies";
const column1Text =
  "Smart CCTV, PA Systems, and Intercom Solutions You Can Trust";
const column2Heading = "Projects";
const column3Heading = "Services";
const column4Heading = "Contact";

const connectHeading = "";

const socialItems = [
  {
    link: "https://www.instagram.com/",
    icon: "icon-instagram",
  },
  {
    link: "https://www.twitter.com/",
    icon: "icon-twitter",
  },
  {
    link: "https://www.facebook.com/",
    icon: "icon-facebook",
  },
  {
    link: "https://www.linkedin.com/company/4x-technologies/?originalSubdomain=in",
    icon: "icon-linkedin",
  },
  {
    link: "https://www.pinterest.com/",
    icon: "icon-pinterest",
  },
];
</script>

<template>
  <div class="site-footer">
    <div class="footer-dots"></div>
    <div class="container">
      <div class="row justify-content-between">

        <!-- Left -->
        <div class="col-lg-4">
          <div class="widget">
            <h3>{{ column1Heading }}</h3>
            <p>{{ column1Text }}</p>
          </div>

          <div class="widget">
            <h3>{{ connectHeading }}</h3>
            <ul class="list-unstyled social">
              <!-- social icons -->
            </ul>
          </div>
        </div>

        <!-- Middle (wider now) -->
        <div class="col-lg-4">
          <div class="widget">
            <h3>{{ column3Heading }}</h3>

            <ul
  class="list-unstyled float-left links"
  style="white-space: nowrap;"
>
  <li><a href="#contact-section">CCTV Installation & Configuration</a></li>
  <li><a href="#contact-section">PA System Installation & Configuration</a></li>
  <li><a href="#contact-section">Intercom Installation & Configuration</a></li>
  <li><a href="#contact-section">Card Access Installation & Configuration</a></li>
  <li><a href="#contact-section">Smart TV Installation & Configuration</a></li>
  <li><a href="#contact-section">Carpark Barrier Installation & Configuration</a></li>
  <li><a href="#contact-section">Alarm System Installation & Configuration</a></li>
  <li><a href="#contact-section">Network Installation & Configuration</a></li>
  <li><a href="#contact-section">PWD System Installation & Configuration</a></li>
</ul>
          </div>
        </div>

        <!-- Right -->
        <div class="col-lg-3">
          <div class="widget">
            <h3>{{ column4Heading }}</h3>

            <address>{{ contactInfo.address }}</address>

            <ul class="list-unstyled links mb-4">
              <li>
                <a :href="'mailto:' + contactInfo.email">
                  <span>{{ contactInfo.email }}</span>
                </a>
              </li>
            </ul>
          </div>
        </div>

      </div>

      <div class="row mt-5">
        <div class="col-12 text-center">
          <p>{{ copyrightText }}</p>
        </div>
      </div>
    </div>
  </div>
</template>
