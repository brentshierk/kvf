<template>

  <div>

  <b-card
    border-variant="light"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2 mr-2 ml-2"
  >
    <b-card>
      <img src="../assets/img1.jpg" alt="">
    </b-card>

    <b-card-text>
       For when you want to get fit and be in the comfort of your own home. I’ve programmed live workout outs that you can follow and cast on your TV screen. I’ll be instructing you throughout the entire workout ensuring proper form! You’ll have access to a workout library filled with full body high intensity workouts that burns more calories in less time.

    </b-card-text>

    <b-button href="#" class="butt"><router-link to="/realtime">Go somewhere</router-link></b-button>
  </b-card>
</div>
</template>



<script>
export default {
    name: 'mealcard'
}
</script>



<style>
.butt{
  background: #A2D618;
  color: ivory;
border: #A2D618;
}

</style>