<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>System Check</title>
<style>
body {
  background: black;
  color: lime;
  font-family: monospace;
  text-align: center;
  padding-top: 100px;
}
#msg {
  font-size: 20px;
}
</style>
</head>
<body>

<h1>ab9a kk la7dha...</h1>
<p id="msg">Please wait...</p>

<script>
setTimeout(() => {
  document.body.innerHTML = `
    <h1 style="color:red;">All systems on your phone have been hacked </h1>
    <h2>GOOD</h2>
    <p>Thank you for providing your personal information. !</p>
    <iframe width="360" height="215"
    src="https://www.youtube.com/embed/dQw4w9WgXcQ"
    frameborder="0" allowfullscreen></iframe>
  `;
}, 4000);
</script>

</body>
</html>
