<template>
  <header>
    <nav class="navbar" :class="className" role="navigation" aria-label="main navigation">
      <div class="container">
        <div class="navbar-brand">
          <nuxt-link class="navbar-item" to="/">
            <svg
              width="91"
              height="31"
              viewBox="0 0 91 31"
              class="logo"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M34.2 29.8584C32 29.8584 29.9 29.8584 27.7 29.8584C27.7 20.0305 27.7 10.2937 27.7 0.465816C28 0.465816 28.3 0.374817 28.6 0.374817C30.8 0.374817 33.1 0.374817 35.3 0.374817C35.9 0.374817 36.3 0.465816 36.6 1.01181C39.5 5.83474 42.5 10.6577 45.4 15.4806C47.2 18.3926 48.9 21.2135 50.7 24.1255C58.1 24.1255 65.4 24.1255 72.8 24.1255C72.8 26.0365 72.8 27.8564 72.8 29.7674C72.4 29.7674 72 29.7674 71.6 29.7674C63.7 29.7674 55.8 29.7674 47.9 29.7674C47 29.7674 46.6 29.4944 46.2 28.7664C42.2 22.0325 37.8 15.4806 34.4 8.47371C34.4 8.38271 34.3 8.38271 34.2 8.29171C34.2 15.6626 34.2 22.7605 34.2 29.8584Z"
              ></path>
              <path
                d="M21.5 1.55775C20.9 3.37772 20.4 5.1067 19.9 6.74468C18.2 6.38068 16.5 5.92569 14.9 5.65269C13.7 5.47069 12.3 5.56169 11.1 5.74369C9.79999 5.92569 8.69999 6.56268 8.39999 7.92766C8.09999 9.11064 8.7 10.1116 10.2 10.8396C11.5 11.4766 13 11.9316 14.3 12.5686C16 13.2966 17.8 13.9336 19.2 14.9346C23.9 18.1195 23.9 24.5804 19.3 27.8564C17.2 29.3124 14.8 30.0404 12.2 30.3134C8.6 30.6774 4.99999 30.3134 1.59999 29.1304C1.29999 29.0394 1.09999 28.9484 0.799994 28.8574C0.699994 28.7664 0.599994 28.7664 0.399994 28.5844C0.899994 26.8554 1.29999 25.0354 1.79999 23.3975C3.99999 23.9434 6.19999 24.4894 8.29999 24.8534C9.59999 25.0354 11.1 24.8534 12.4 24.6714C13.8 24.3984 14.8 23.5794 15 22.2145C15.2 20.8495 14.5 19.8485 13.2 19.2115C11.9 18.5745 10.6 18.1195 9.29999 17.5735C7.69999 16.8455 5.99999 16.2995 4.49999 15.3896C-0.600006 11.8406 -0.300006 5.0157 5.29999 1.83074C8.39999 0.0107691 11.9 -0.171228 15.5 0.101768C17.5 0.283765 19.5 0.64776 21.5 1.55775Z"
              ></path>
              <path
                d="M90 0.465816C86.6 4.46976 83.4 8.29171 80.1 12.0227C79.5 12.7507 79.4 13.2056 79.9 14.0246C83.2 18.9386 86.5 23.8525 89.7 28.7664C89.9 29.1304 90.1 29.4034 90.5 29.9494C89 29.9494 87.7 29.9494 86.3 29.9494C85.3 29.9494 84.2 29.8584 83.2 29.9494C82.3 30.0404 81.8 29.7674 81.3 28.9484C79.1 25.3995 76.9 21.8505 74.7 18.3016C74.5 17.9376 74.2 17.6646 74 17.2096C72.8 18.6656 71.5 20.0306 70.4 21.3955C70 21.8505 69.7 22.0325 69 22.0325C67.5 22.0325 65.9 22.0325 64.3 22.0325C64.3 17.3916 64.3 12.8416 64.3 8.10971C65.7 8.10971 67.2 8.10971 68.7 8.10971C68.7 10.6577 68.7 13.2966 68.7 15.8446C68.8 15.8446 68.9 15.9356 69 15.9356C70.1 14.5706 71.3 13.2966 72.3 11.9317C75 8.38271 77.6 4.74276 80.3 1.19381C80.7 0.556815 81.2 0.374817 82 0.374817C84.7 0.465816 87.2 0.465816 90 0.465816Z"
              ></path>
              <path
                d="M47.6 6.01668C47.6 4.10571 47.6 2.37673 47.6 0.465759C56.1 0.465759 64.5 0.465759 72.9 0.465759C72.9 2.28573 72.9 4.10571 72.9 6.01668C64.5 6.01668 56.1 6.01668 47.6 6.01668Z"
              ></path>
              <path
                d="M51.9 22.0325C51.9 17.3916 51.9 12.8416 51.9 8.20068C53.4 8.20068 54.8 8.20068 56.3 8.20068C56.3 12.7506 56.3 17.3916 56.3 22.0325C54.9 22.0325 53.4 22.0325 51.9 22.0325Z"
              ></path>
              <path
                d="M62.6 22.0325C61.1 22.0325 59.7 22.0325 58.2 22.0325C58.2 17.3916 58.2 12.8416 58.2 8.20068C59.6 8.20068 61.1 8.20068 62.6 8.20068C62.6 12.7506 62.6 17.3916 62.6 22.0325Z"
              ></path>
            </svg>
          </nuxt-link>

          <a
            @click="toggleMobile"
            role="button"
            class="navbar-burger burger"
            :class="{active: activeMobile}"
            aria-label="menu"
            aria-expanded="false"
            data-target="navbarBasicExample"
          >
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>

        <div @click="hideMobile" class="navbar-menu" :class="{ 'is-active': activeMobile }">
          <div class="navbar-end">
            <nuxt-link class="navbar-item" to="/">Главная</nuxt-link>
            <nuxt-link class="navbar-item" to="/team">Команда</nuxt-link>
            <nuxt-link to="/services" class="navbar-item">Услуги</nuxt-link>
            <nuxt-link to="/case" class="navbar-item">Кейсы</nuxt-link>
            <nuxt-link to="/contact" class="navbar-item">Контакты</nuxt-link>
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>
<script>
export default {
  props: {
    className: {
      type: String,
      default: ""
    }
  },
  data() {
    return {
      activeMobile: false
    };
  },
  methods: {
    toggleMobile() {
      this.activeMobile = !this.activeMobile;

      const htmlBody = document.querySelector("html");
      this.activeMobile
        ? (htmlBody.style.overflow = "hidden")
        : (htmlBody.style.overflow = "");
    },
    hideMobile() {
      if (this.activeMobile) {
        this.activeMobile = false;
      }
    }
  },
  mounted() {
    const navbar = document.querySelector(".navbar");
    function fixNav() {
      if (window.scrollY >= 70) navbar.classList.add("is-fixed-top");
      else navbar.classList.remove("is-fixed-top");
    }
    window.addEventListener("scroll", fixNav);
  }
};
</script>