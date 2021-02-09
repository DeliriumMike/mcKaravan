<template>
  <div class="header" bg-dark>
    <v-container>
      <div class="header__content">
        <div class="logo">
          <p>Karavan</p>
          <img src="@/assets/img/logo24.svg" alt="logo24">
        </div>
        <div class="phone">
          <img src="@/assets/img/phohe-icon.svg" alt="phone-icon">
          <p>8-800-555-35-35</p>
        </div>
      </div>
    </v-container>
  </div>
</template>

<script>
  export default {

  }
</script>

<style lang="scss">
  .header {
    background-color: #000000;

    .header__content {
      justify-content: space-between;
      align-items: center;
      display: flex;

      .logo {
        display: flex;

        p {
          font-size: 70px;
          color: #FFFFFF;
        }
      }

      .phone {
        display: flex;

        p {
          color: #FFFFFF;
          font-size: 27px;
          margin-left: 7px;
        }
      }
    }
  }
</style>