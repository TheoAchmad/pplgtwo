<!DOCTYPE html>
<html>
  <body>
    <h1>intaaaaaa masiii marahhh yaaa??</h1>
    <img src="IMG_20241124_023550.jpg" width="100%" />
    <h1>maaafinnn ezaaaa yaaaaa??</h1>
    <button id="btn_mau" onclick="alert('trimakasiiii intaaaaa baikannn yaaaaa :D')">iya</button>&nbsp;
    <button id="btn_gamau" onclick="gamau(this)" style="position: absolute">
      ga
    </button>
  </body>
  <script>
    function gamau(id) {
      var mau = document.getElementById("btn_mau");
      var i = Math.floor(Math.random() * 300) + 1;
      var j = Math.floor(Math.random() * 100) + mau.offsetTop;
      id.style.left = i + "px";
      id.style.top = j + "px";
    }
  </script>
</html>
