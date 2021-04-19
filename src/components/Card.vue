<template>
  <div class="column is-one-quarter">
      <div class="card">
        <figure class="image is-128x128">
          <img v-bind:src=img>
      </figure>
      <h3 class="is-size-5">{{msg}}</h3>
      <p class="has-text-link-dark">{{price}}</p>
      <button class="button is-info"> Заказать </button>
      </div>
  </div>
</template>

<script>
import 'bulma/css/bulma.css'
export default {
  name: 'Card',
  props: {
    img: String,
    msg: String,
    price: Number
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped >
.card{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 10px;
}
figure{
  margin-bottom: 20px;
}
button{
  align-self: flex-end;
}
</style>
