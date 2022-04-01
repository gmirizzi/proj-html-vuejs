<template>
  <div id="infobar" class="py-3">
    <div class="container d-flex justify-content-between">
      <div id="openhours">
        <font-awesome-icon icon="fa-solid fa-clock" /> Open Hours: Mon - Sat -
        9:00 - 18:00
      </div>
      <div id="contacts" class="d-flex">
        <div id="phone">
          <font-awesome-icon icon="fa-solid fa-phone" /> +1 (305) 1234-5678
        </div>
        <div id="mail" class="mx-4">
          <font-awesome-icon icon="fa-solid fa-envelope" /> hello@example.com
        </div>
        <div id="social">
          <!-- FIXME: icone social -->
          <a href=""
            ><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
              <!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
              <path
                d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z"
              /></svg></a
          ><a href=""></a><a href=""></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "InfoBar",
};
</script>

<style lang="scss" scoped>
#infobar {
  background-color: #21333eff;
  color: #c0c3d0ff;
}
</style>
