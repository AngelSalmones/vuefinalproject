<template>
  <div class="notification-banner">
    <div class="container">
      <h2>Salmones Store:</h2>
      <ul class="list-unstyled">
        <li>Bienvenidos a la tienda virtaul<b></b></li>
        <li>Tienda especializada en: <b></b></li>
        <li>Codigo de descuento: <b>verano_2020</b></li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.notification-banner {
  background-color: color(primary, light);
  padding: spacer(3) 0;
  margin-bottom: spacer(3);

  @include ie11() {
    .container {
      > * {
        max-width: 400px;
      }
    }
  }
  

  h2 {
    margin-top: 0;
  }

  ul {
    margin-bottom: 0;
  }
}
</style>
