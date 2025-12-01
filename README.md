<!DOCTYPE html>
<html>
<head>
<style>
  .typewriter {
    font-size: 60px;
    font-family: monospace;
    overflow: hidden;
    border-right: 4px solid orange;
    white-space: nowrap;
    animation: typing 3s steps(20) infinite, blink 0.7s infinite;
  }
  @keyframes typing {
    0% { width: 0 }
    50% { width: 100% }
    100% { width: 0 }
  }
  @keyframes blink {
    50% { border-color: transparent }
  }
</style>
</head>
<body style="background:#000; color:#0f0; display:flex; justify-content:center; align-items:center; height:100vh;">
  <div class="typewriter">Hello World!</div>
</body>
</html>

彩虹跑馬燈（超級俗氣但超好玩）

HTML<!DOCTYPE html>
<html>
<head>
<style>
  .rainbow {
    font-size: 80px;
    font-weight: bold;
    background: linear-gradient(90deg, red, orange, yellow, green, blue, indigo, violet);
    -webkit-background-clip: text;
    color: transparent;
    animation: wave 3s infinite, move 5s infinite linear;
  }
  @keyframes wave {
    0%,100% { transform: translateY(0); }
    50% { transform: translateY(-20px); }
  }
  @keyframes move {
    0% { background-position: 0% 50%; }
    100% { background-position: 100% 50%; }
  }
</style>
</head>
<body style="background:black; display:flex; justify-content:center; align-items:center; height:100vh;">
  <div class="rainbow">Hello World!</div>
</body>
</html>
