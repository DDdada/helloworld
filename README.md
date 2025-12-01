<!DOCTYPE html>
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
