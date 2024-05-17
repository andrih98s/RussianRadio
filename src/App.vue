<template>
  <div id="app">
    <div class="container">
      <h1>Русское ✯ Радио</h1>
      <h4 class="animated-text">⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣼⢻⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⢤⣄⣀⣀⣀⣰⡇⠈⣧⣀⣀⣀⣀⣀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠻⢦⡀⠀⠀⠀⠀⢀⣠⠾⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣹⠃⠀⡀⠀⢿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⣠⠔⠂⠀⠀⠀⢠⣏⣴⠞⠛⢦⣜⣧⠀⠀⠀⠀⠢⣄⡀⠀⠀⠀⠀
        ⠀⠀⢠⣖⡿⡋⠀⠀⠀⠀⠀⠾⠋⠀⠀⠀⠀⠉⠻⡄⠀⠀⠀⠀⢝⢿⣱⣄⠀⠀
        ⠀⡜⣿⣨⡾⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠲⣤⡀⠀⠀⠀⠀⠀⠈⢳⣇⣿⢡⠀
        ⢰⣇⣟⣵⠃⠀⠀⠀⠀⠀⠀⢀⣴⣦⡤⠀⠀⠈⠻⣷⡀⠀⠀⠀⠀⠈⣯⡻⢸⡆
        ⡆⣿⡾⡅⠀⠀⠀⠀⠀⢀⣴⣿⣿⣏⠀⠀⠀⠀⠀⠹⣿⡆⠀⠀⠀⠀⢨⢻⣾⢱
        ⣷⡘⣱⠇⠀⠀⠀⠀⠀⠀⠹⠋⠈⠻⣷⣄⠀⠀⠀⠀⣿⣿⠀⠀⠀⠀⠘⣧⢋⣾
        ⡼⣷⡿⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠻⣷⣄⠀⢀⣿⣿⠀⠀⠀⠀⢰⢻⣾⢇
        ⢳⣌⠇⣿⠀⠀⠀⠀⠀⠀⣴⢶⣤⣀⡀⠀⠈⢻⣷⣾⣿⠏⠀⠀⠀⠀⣿⠸⣡⡞
        ⠀⡿⢷⣿⡸⣄⠀⢀⣴⡾⠉⠀⠈⠛⠿⢿⣿⣿⡿⠿⣷⣄⠀⠀⢠⡇⣿⡾⢛⠀
        ⠀⠘⢦⣝⡣⢿⡦⡈⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⠋⢀⣴⡿⣘⣭⡶⠃⠀
        ⠀⠀⠀⠹⣛⠿⠷⡹⣦⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⢟⠾⠟⣛⠝⠀⠀⠀
        ⠀⠀⠀⠀⠈⠛⡿⠿⠶⢛⣫⣤⡶⣒⡶⠶⣖⠶⣶⣍⣛⠚⠿⣟⠛⠁⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠈⠙⠛⠛⠋⢡⠞⠁⠀⠀⠈⠻⣮⠙⠛⠛⠋⠁⠀⠀⠀⠀⠀⠀</h4>
      <audio controls>
        <source src="https://rusradio.hostingradio.ru/rusradio128.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
      <footer>
        <p>All rights reserved by Andrey © 2024-2025</p>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
body {
  font-family: 'Roboto', sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: linear-gradient(135deg, #2c3e50, #4ca1af);
  margin: 0;
  color: #ffffff;
}

.container {
  text-align: center;
  background: rgba(44, 62, 80, 0.9);
  padding: 30px 20px;
  border-radius: 15px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
  max-width: 90%;
}

h1 {
  margin-bottom: 20px;
  font-size: 1.8rem;
  color: #ecf0f1;
}
h4 {
  color: #4ca1af;
  animation: slideRight 10s linear infinite;
}@keyframes slideRight {
   0% {
     transform: translatey(+20%);
   }
   100% {
     transform: translatey(0%);
   }
 }
audio {
  width: 100%;
  max-width: 400px;
  border-radius: 5px;

}

footer {
  margin-top: 20px;
  font-size: 0.9rem;
  color: #bdc3c7;
}

@media (max-width: 600px) {
  h1 {
    font-size: 1.5rem;
  }

  audio {
    max-width: 300px;
  }
}
</style>
