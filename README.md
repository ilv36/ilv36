<!DOCTYPE html>
<html>
<head>
<style>
@keyframes blinker {
  50% {
    opacity: 0;
  }
}
.blink {
  color: red;
  animation: blinker 1s linear infinite;
}
</style>
</head>
<body>

<p class="blink">This text will blink</p>

</body>
</html>
