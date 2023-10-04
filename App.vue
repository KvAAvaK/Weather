<script>
</script>
<template>
  <head>
    <title>Weather app</title>
  </head>
  <body>
  <header class="header">
    <div class="form">
      <form class="input-form">
        <input class="city-name-input" placeholder="Enter your city" type="text">
        <label class="data-text" for="date">Date : </label>
        <select class="drop-down-data" id="date">
          <option>1</option>
          <option>2</option>
          <option>3</option>
          <option>4</option>
          <option>5</option>
          <option>6</option>
          <option>7</option>
        </select>
      </form>
    </div>
  </header>
  <div class="main-day">
      <span class="wick-dayInform-main">
        MONDAY, MAY 23<br>
        27°C<br>
        <span class="real-time">
        14:35<br>
      </span>
        <span class="real-feel">
        Real Feel 25°C<br>
        </span>
        <span class="humidity">
        Humidity 61%
        </span>
      </span>
    <img alt="Cloudy Iconixar Flat icon" loading="lazy" decoding="async" data-nimg="1" class="img-mainDay"
         src="https://cdn-icons-png.flaticon.com/512/1163/1163661.png?ga=GA1.1.1110742611.1694168823"
         style="color: transparent;">
  </div>
  <div class="table">
    <div class="first-row">
      <div class="first-1">
        <span class="table-inform">TUE<br>26°C</span>
        <img alt="Sun Iconixar Flat icon" loading="lazy" decoding="async" data-nimg="1" class="img-table"
             src="https://cdn-icons-png.flaticon.com/512/1163/1163662.png?ga=GA1.1.1110742611.1694168823" style="color: transparent;">
      </div>
      <div class="first-2">
        <span class="table-inform">WED<br>25°C</span>
        <img alt="Cloudy Iconixar Flat icon" loading="lazy" decoding="async" data-nimg="1" class="img-table"
             src="https://cdn-icons-png.flaticon.com/512/1163/1163657.png?ga=GA1.1.1110742611.1694168823" style="color: transparent;">
      </div>
      <div class="first-3">
        <span class="table-inform">THU<br>24°C</span>
        <img alt="Sun Iconixar Flat icon" loading="lazy" decoding="async" data-nimg="1" class="img-table"
             src="https://cdn-icons-png.flaticon.com/512/1163/1163662.png?ga=GA1.1.1110742611.1694168823" style="color: transparent;">
      </div>
    </div>
    <div class="second-row">
      <div class="second-1">
        <span class="table-inform">FRI<br>25°C</span>
        <img alt="Storm Iconixar Flat icon" loading="lazy" decoding="async" data-nimg="1" class="img-table"
             src="https://cdn-icons-png.flaticon.com/512/1163/1163659.png?ga=GA1.1.1110742611.1694168823" style="color: transparent;">
      </div>
      <div class="second-2">
        <span class="table-inform">SAT<br>26°C</span>
        <img alt="Cloudy Iconixar Flat icon" loading="lazy" decoding="async" data-nimg="1" class="img-table"
             src="https://cdn-icons-png.flaticon.com/512/1163/1163660.png?ga=GA1.1.1110742611.1694168823" style="color: transparent;">
      </div>
      <div class="second-3">
        <span class="table-inform">SUN<br>27°C</span>
        <img alt="Cloudy Iconixar Flat icon" loading="lazy" decoding="async" data-nimg="1" class="img-table"
             src="https://cdn-icons-png.flaticon.com/512/1163/1163661.png?ga=GA1.1.1110742611.1694168823" style="color: transparent;">
      </div>
    </div>
  </div>
  </body>
</template>>

<style>
body {
  margin: 0;
  min-height: 100vh;
  background: rgb(76,90,102);
  background: linear-gradient(5deg, rgba(76,90,102,1) 0%, rgba(174,191,205,1) 100%);
  background-size: cover;
  background-repeat: no-repeat;

}

header {
  height: 40px;
}

.form {
  padding: 15px;
  line-height: 40px;
  display: flex;
  justify-content: center;
  border-radius: 10px;
}


.city-name-input {
  outline: none;
  padding: 5px;
  font-size: 15px;
  font-family: sans-serif;
  color: #fcfcfc;
  margin: 0 5px;
  background: transparent;
  border: 0;
  border-bottom: 2px solid rgb(50, 87, 96);
  text-align: center;

}

.city-name-input::placeholder{
  text-align: center;
  color: rgb(50, 87, 96);
  font-family: sans-serif;
  font-size: 20px;
}
.drop-down-data{

  text-align: center;
  font-size: 15px;
  color: rgb(50, 87, 96);
  background:transparent;
  outline: none;
  border: 0;
}

option{
  color: white;
  background: rgb(76,90,102);
  outline: none;
}


.data-text {
  color: rgb(50, 87, 96);
  font-family: sans-serif;
  font-size: large;
}

.main-day {
  display: flex;
  justify-content: space-between;
  background: rgb(50, 87, 96);
  margin: 3% 15% 0;
  padding: 5%;
}

.wick-dayInform-main {
  color: white;
  font-family: sans-serif;
  font-size: 40px;
}
.real-time{
  font-size: 35px;
}
.real-feel{
  font-size: 30px;
}
.humidity{
  font-size: 30px;
}

.img-mainDay {
  height: 200px;
}
.first-row, .second-row{
  display: flex;
  margin: 0 15%;
}

.table-inform{
  padding: 7%;
  font-size: 25px;
  color: white;
  font-family: sans-serif;
}
.first-1, .first-3 {
  border: 5px solid rgb(154, 175, 184);
  width: 33%;
  margin-bottom: -5px;
  display: flex;
  justify-content: space-between;

}
.first-2{
  border: 5px solid rgb(154, 175, 184);
  width: 33%;
  margin:0 -5px -5px -5px;
  display: flex;
  justify-content: space-between;

}
.second-1, .second-3 {
  border: 5px solid rgb(154, 175, 184);
  width: 33%;
  display: flex;
  justify-content: space-between;
}
.second-2{
  border: 5px solid rgb(154, 175, 184);
  width: 33%;
  margin:0 -5px 0 -5px;
  display: flex;
  justify-content: space-between;
}
.img-table{
  width: 75px;
  height: 75px;
  padding: 7%;
  display: flex;
  justify-content: space-between;
}

</style>