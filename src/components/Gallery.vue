<template>
  <div>
    <div class = "speech-wrapper">
      <div class = "speech-bubble">
        <h3>Gallery</h3>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data(){
      return{

      }
    }
  }
</script>

<style scoped>
.speech-wrapper {
  margin-bottom: 12px;
}
.speech-bubble {
  width: 300px;
  height: 65px;
  font-size: 18px;
  -webkit-clip-path: polygon(0% 0%, 100% 0%, 100% 75%, 65% 75%, 66% 96%, 50% 75%, 0 75%);
  clip-path: polygon(0% 0%, 100% 0%, 100% 75%, 65% 75%, 66% 96%, 50% 75%, 0 75%);
  background-color: #6C7C59;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  text-align: center;
}
h3 {
  color: white;
  font-weight: lighter;
  margin-top: 12px;
}
</style>
