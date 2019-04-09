<template>
  <div id = "parent">
    <div id = "wrapper">
      <div class = "speech-wrapper">
        <div class = "speech-bubble">
          <h3>Refreshments</h3>
        </div>
      </div>
      <div id="main-text">
        <p>Welcome to The Georgian Theatre, Stockton-on-Tees – Teesside’s longest running and one of north-east England’s finest independent music venues…<br><br>
          We provide a great programme of live music – and when we throw our doors open, anyone can pop by for a drink and a chat in our bar area - serving fine real ales, craft beers, gins and ciders.<br><br>
          We’re child and dog friendly  – and we think The Georgian Theatre is a really great place just to gather and hang out…<br><br>
          Although we don't currently open regularly during the day for food and drink; we offer a catering service for special events and bookings.</p>
      </div>
      <div id="bar">
        <div class="g-container">
            <div id="container">
              <div class="g-item">
              <h3>Bar Opening</h3>
              <p>WE OPEN OUR BAR FROM 5:00PM ON THE NIGHTS WE HAVE EVENTS RUNNING.<br>NON-TICKET HOLDERS ARE WELCOME TO USE OUR BAR.</p><br>
              <p>SERVING...</p>
              <p>REAL ALES</p>
              <p>PREMIUM GINS</p>
              <p>FRESH COFFEES</p>
            </div>
          <div class="g-item">
            <img src="../assets/gtbar.jpg">
          </div>
        </div>
        </div>
      </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
    }
  },
  methods:{

    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.g-container {
  width: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-evenly;
  text-align: center;
}
.g-container div {
  min-width: 140px;
  min-height: 130px;
  text-align: center;
}
.g-item {
  color: white;
}
#container {
  width: 100%;
  padding: 10px;
  margin: 10px;
  background-color: #6C7C59;
}
#parent {
  width: 100%;
  text-align: center;
  height: 100%;
  position: fixed;
}
#bg-container {
  height: 100vh;
  z-index: -100;
}
#wrapper {
  position: relative;
}
#main-text {
  background: #3A3C39;
  color: white;
  margin: 10px;
  padding: 20px;
}
p {
  margin: 0px;
}
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
img {
  max-width: 50%;
  margin-top: 5px;
}
</style>
