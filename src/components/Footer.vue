<script setup>
import { contactInfo } from "../data/items";

const copyrightText = "Copyright 2025, All rights reserved.";
const column1Heading = "About 4x Technologies";
const column1Text =
  "At 4X Technologies, we provide cutting-edge solutions in security, safety, building management, and access control. Our services are designed to enhance the security, efficiency, and safety of your business and facilities, offering peace of mind with the most reliable systems available..";
const column2Heading = "Projects";
const column3Heading = "Services";
const column4Heading = "Contact";

const connectHeading = "Connect";

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
      <div class="row">
        <div class="col-lg-4">
          <div class="widget">
            <h3>{{ column1Heading }}</h3>
            <p>{{ column1Text }}</p>
          </div>
          <div class="widget">
            <h3>{{ connectHeading }}</h3>
            <ul class="list-unstyled social">
              <!-- <li style="margin-right: 4px">
                <a :href="socialItems[0].link"
                  ><span :class="socialItems[0].icon"></span
                ></a>
              </li>
              <li style="margin-right: 4px">
                <a :href="socialItems[1].link"
                  ><span :class="socialItems[1].icon"></span
                ></a>
              </li>
              <li style="margin-right: 4px">
                <a :href="socialItems[2].link"
                  ><span :class="socialItems[2].icon"></span
                ></a>
              </li> -->
              <li style="margin-right: 4px">
                <a :href="socialItems[3].link"
                  ><span :class="socialItems[3].icon"></span
                ></a>
              </li>
              <!-- <li>
                <a :href="socialItems[4].link"
                  ><span :class="socialItems[4].icon"></span
                ></a>
              </li> -->
            </ul>
          </div>
        </div>
        <!-- <div class="col-lg-2 ml-auto">
          <div class="widget">
            <h3>{{ column2Heading }}</h3>
            <ul class="list-unstyled float-left links">
              <li><a href="#">La Lega Stadium</a></li>
              <li><a href="#">France Building</a></li>
              <li><a href="#">22 New Homes</a></li>
              <li><a href="#">Manage Center</a></li>
              <li><a href="#">Sports Hall</a></li>
            </ul>
          </div>
        </div> -->
        <div class="col-lg-2 ml-auto">
          <div class="widget">
            <h3>{{ column3Heading }}</h3>
            <ul class="list-unstyled float-left links">
              <li><a href="#contact-section">CCTV & Access Control</a></li>
              <li><a href="#contact-section">Fire Alarm Systems</a></li>
              <li><a href="#contact-section">PA & AV Solutions</a></li>
              <li><a href="#contact-section">Car Park Barrier Systems</a></li>
              <li><a href="#contact-section">Elevator Systems</a></li>
              <li>
                <a href="#contact-section">Pwd Toilet Emergency Call System</a>
              </li>
              <li><a href="#contact-section">Intercom System</a></li>
              <li><a href="#contact-section">Turnstile Installation</a></li>
              <li><a href="#contact-section">Building Access Control</a></li>
              <li><a href="#contact-section">Technical Support</a></li>
            </ul>
          </div>
        </div>
        <div class="col-lg-3 ml-auto">
          <div class="widget">
            <h3>{{ column4Heading }}</h3>
            <address>{{ contactInfo.address }}</address>
            <ul class="list-unstyled links mb-4">
              <li>
                <a :href="'tel://' + contactInfo.phone1">{{
                  contactInfo.phone1
                }}</a>
              </li>
              <li>
                <a :href="'tel://' + contactInfo.phone2">{{
                  contactInfo.phone2
                }}</a>
              </li>
              <li>
                <a :href="'mailto:' + contactInfo.email"
                  ><span>{{ contactInfo.email }}</span></a
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="row mt-5">
        <div class="col-12 text-center">
          <p>
            {{ copyrightText }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
