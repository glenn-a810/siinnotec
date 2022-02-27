<template>
  <div>
    <img src="./assets/logo.png" alt="logo" />
    <a>ABOUT</a>
    <a>SERVICES</a>
    <a>EXPERIENCES</a>
    <a>CONTACT</a>
  </div>

  <div>
    <img src="./assets/carousel/1.jpg" alt="carousel1" />
  </div>

  <div class="parent">
    <div class="child">
      <img
        src="./assets/about_overview_1.png"
        alt="about_overview"
        class="overview"
      />
    </div>
    <div class="child">
      <p>Greeting, We are SI Innotec</p>
      <p>
        SI Innotec is specialized in the Marine Engineering, Renewable Energy,
        IT Renovation, and Productivity Improvement consulting.
      </p>
      <p>
        We provide opportunity to client purchase best quality with competitive
        price, and our professional teams are best doing for the valued
        customers.
      </p>
    </div>
  </div>

  <div class="parent">
    <div class="child">
      <p>INNOVATION</p>
      <p>Find and develop a new technology product</p>
    </div>
    <div class="child">
      <p>GLOBAL MARKETING</p>
      <p>Expand a good global marketing area</p>
    </div>
    <div class="child">
      <p>CUSTOMIZED SERVICES</p>
      <p>Provide the finest customized service to clients</p>
    </div>
  </div>

  <div>
    <span>Service Outline</span>
    <span> | </span>
    <span>Recent Projects</span>
  </div>

  <div>
    <p>Our Services</p>
    <p>Service Card</p>
  </div>

  <div>
    <p>Experiences List</p>
    <p>Experiences Portfolio</p>
  </div>

  <div>
    <p>Contact Us</p>
    <p>Google Maps</p>
  </div>

  <div>
    <p>Partners List</p>
  </div>

  <div>
    <span>Footer Company Info</span>
    <span> | </span>
    <span>Footer Quick Links</span>
    <span> | </span>
    <span>Contact Info</span>
    <p>Copyright</p>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  font-family: Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto,
    "Helvetica Neue", "Segoe UI", "Apple SD Gothic Neo", "Noto Sans KR",
    "Malgun Gothic", sans-serif;
}

.overview {
  width: 50%;
  height: 100%;
}

.parent {
  display: flex;
}

.parent .child {
  flex: 1;
}
</style>
