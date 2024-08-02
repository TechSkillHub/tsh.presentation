<template>
  <v-parallax
    style="height: 100vh; bottom: 0;"
    :src="require('@/assets/images/hire-me.jpg')"
    alt="Hire me"
  >
    <div class="d-flex hire-me px-4 hire-me-content">
      <div class="content d-flex flex-column">
        <div class="section-title">Dúvidas?</div>

        <div class="help" data-aos="fade-bottom">
          Entre em contato com nossa equipe!
        </div>
        <v-btn
          class="mx-auto"
          rounded
          large
          color="green"
          elevation="0"
          :href="mail"
          target="_blank"
          data-aos="fade-bottom"
        >
          WhatsApp
        </v-btn>
      </div>
    </div>
  </v-parallax>
</template>

<script>
import Constants from '@/constants'

export default {
  data() {
    return {
      mail: Constants.HIRE_ME
    }
  }
}
</script>

<style lang="scss" scoped>
::v-deep .v-parallax__image {
  object-fit: cover;
  height: 100vh;
  top: 0;
  transform: translate(-50%, 0px) !important;
}

::v-deep .v-parallax__content {
  background-color: #2320204a;
  padding: 0 !important;
}
.hire-me-content {
  margin: auto;
  .section-title {
    font-size: 7rem;
    font-weight: 600;
    @media(max-width: 768px) {
      font-size: 5rem;
    }
  }
}
.hire-me {
  .help {
    text-align: center;
    font-size: 1.5em;
    margin-bottom: 1rem;
  }
}

@media screen and (max-width: 767px) {
  .hire-me-content {
    margin-left: 0 !important;
  }
}
</style>
