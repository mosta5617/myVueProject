<template>
  <!-- <div>{{ greet }} {{ name }} </div> -->

  <!-- <div v-html="hack"></div> -->
  <!-- <div v-bind:id="headingID">Heading</div> -->
  <button v-bind:disabled="isDisabled">Bind</button>

</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      greet: 'Hello',
      name: 'Uranus How are you?',
      channel: '<b> Fruits Archive </b>',
      hack: '<a href="#" onclick=alert(You have been hacked)> Win a prize! <a/>',
      headingID: 'heading ID',
      isDisabled: true
    };
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
