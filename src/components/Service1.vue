<script setup>
import { themeColor } from "../data/items";

const service1Heading = "Services";
const service1SubHeading = "Our Core Services";

const services = [
  { icon: '📷', title: 'CCTV Installation', subtitle: '& Configuration' },
  { icon: '🔊', title: 'PA System Installation', subtitle: '& Configuration' },
  { icon: '📞', title: 'Intercom Installation', subtitle: '& Configuration' },
  { icon: '🪪', title: 'Card Access Installation', subtitle: '& Configuration' },
  { icon: '📺', title: 'Smart TV Installation', subtitle: '& Configuration' },
  { icon: '🚧', title: 'Carpark Barrier Installation', subtitle: '& Configuration' },
  { icon: '🚨', title: 'Alarm System Installation', subtitle: '& Configuration' },
  { icon: '🌐', title: 'Network Installation', subtitle: '& Configuration' },
  { icon: '♿', title: 'PWD System Installation', subtitle: '& Configuration' },
];

const highlights = [
  {
    icon: '🛡️',
    title: 'Professional Team',
    text: 'Experienced and certified engineers you can trust.'
  },
  {
    icon: '⚙️',
    title: 'Reliable Solutions',
    text: 'We deliver dependable systems built for long-term performance.'
  },
  {
    icon: '🎧',
    title: 'End-to-End Support',
    text: 'From consultation to installation and after-sales support.'
  },
  {
    icon: '🏢',
    title: 'For Every Environment',
    text: 'Commercial, industrial solutions tailored to your needs.'
  }
];
</script>

<template>
  <section class="services-section" id="services-section">
    <div class="container">

      <div class="top-layout">

        <!-- Left Content -->
        <div class="left-content">
          <p class="tag">SERVICES</p>
          <h2>Our Core Services</h2>
          <div class="line"></div>

          <p class="description">
            At 4X Technologies, we provide professional installation,
            configuration, maintenance, and technical support for security,
            communication, and building management systems across Singapore.
          </p>

          <p class="description">
            Our experienced team delivers reliable solutions for commercial,
            industrial, and residential projects, ensuring safety, seamless
            communication, and efficient daily operations with long-term
            performance you can trust.
          </p>

          <div class="image-card">
            <img
              src="/cctv.jpg"
              alt="Security Camera"
            />

            
          </div>
        </div>

        <!-- Right Cards -->
        <div class="right-grid">
          <div
            class="service-card"
            v-for="(item, index) in services"
            :key="index"
          >
            <div class="icon-box">
              {{ item.icon }}
            </div>

            <div class="service-text">
              <h4>{{ item.title }}</h4>
              <p>{{ item.subtitle }}</p>
              <div class="mini-line"></div>
            </div>
          </div>
        </div>

      </div>

      <!-- Bottom Highlights -->
      <div class="bottom-highlights">
        <div
          class="highlight-card"
          v-for="(item, index) in highlights"
          :key="index"
        >
          <div class="icon-box small">
            {{ item.icon }}
          </div>

          <div>
            <h5>{{ item.title }}</h5>
            <p>{{ item.text }}</p>
          </div>
        </div>
      </div>

    </div>
  </section>
</template>

<style scoped>
* {
  box-sizing: border-box;
}

.services-section {
  background: #f5f7fb;
  padding: 70px 0;
  font-family: "Segoe UI", sans-serif;
}

.container {
  width: 92%;
  max-width: 1320px;
  margin: auto;
}

.top-layout {
  display: grid;
  grid-template-columns: 1fr 1.1fr;
  gap: 40px;
  align-items: start;
}

/* LEFT */

.tag {
  color: #1456d9;
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 1px;
  margin-bottom: 10px;
}

h2 {
  font-size: 42px;
  font-weight: 800;
  color: #071b5a;
  margin: 0;
  line-height: 1.2;
}

.line {
  width: 60px;
  height: 4px;
  background: #1456d9;
  border-radius: 10px;
  margin: 20px 0 24px;
}

.description {
  color: #5d6778;
  font-size: 16px;
  line-height: 1.8;
  margin-bottom: 20px;
}

.image-card {
  margin-top: 30px;
  position: relative;
  border-radius: 28px;
  overflow: hidden;
}

.image-card img {
  width: 100%;
  height: 280px;
  object-fit: cover;
  display: block;
}

.floating-badge {
  position: absolute;
  left: 20px;
  bottom: 20px;
  background: #082d7c;
  color: white;
  padding: 14px 18px;
  border-radius: 18px;
  display: flex;
  gap: 12px;
  align-items: center;
  font-size: 14px;
}

/* RIGHT */

.right-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 16px;
}

.service-card {
  background: white;
  border-radius: 20px;
  padding: 20px;
  display: flex;
  gap: 16px;
  align-items: center;
  min-height: 110px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.04);
}

.icon-box {
  width: 58px;
  height: 58px;
  border-radius: 50%;
  background: #f1f5ff;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 24px;
  flex-shrink: 0;
}

.service-card h4 {
  margin: 0;
  font-size: 18px;
  color: #14224d;
  line-height: 1.4;
  font-weight: 700;
}

.service-card p {
  margin: 2px 0 0;
  font-size: 15px;
  color: #14224d;
  font-weight: 500;
}

.mini-line {
  width: 20px;
  height: 3px;
  background: #1456d9;
  border-radius: 10px;
  margin-top: 10px;
}

/* BOTTOM */

.bottom-highlights {
  margin-top: 32px;
  background: white;
  border-radius: 24px;
  padding: 28px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.04);
}

.highlight-card {
  display: flex;
  gap: 14px;
  align-items: flex-start;
}

.icon-box.small {
  width: 52px;
  height: 52px;
  font-size: 20px;
}

.highlight-card h5 {
  margin: 0 0 6px;
  font-size: 16px;
  color: #1456d9;
}

.highlight-card p {
  margin: 0;
  font-size: 14px;
  color: #5d6778;
  line-height: 1.6;
}

/* RESPONSIVE */

@media (max-width: 1200px) {
  .top-layout {
    grid-template-columns: 1fr;
  }

  .right-grid {
    grid-template-columns: 1fr;
  }

  .bottom-highlights {
    grid-template-columns: 1fr;
  }

  h2 {
    font-size: 34px;
  }
}
</style>