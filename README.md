# praini-nm-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!DOCTYPE html><html><head><style>
body{font-family:Arial;text-align:center;margin-top:100px}
input{margin:5px;padding:5px}
</style></head><body>
<h2>Login</h2>
<input id="u" placeholder="Username"><br>
<input id="p" type="password" placeholder="Password"><br>
<button onclick="login()">Login</button>
<p id="msg"></p>
<script>
function login(){let u=u.value,p=p.value;
if(u==="admin"&&p==="1234")msg.textContent="Login Successful!";
else msg.textContent="Invalid Credentials";}
</script>
</body></html>

</body>
</html>
