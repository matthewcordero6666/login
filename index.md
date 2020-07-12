<html>
<head>
<title>login</title>
</head>
<body>
<h1>logged in</h1>
<script>
function run(){
var password = prompt("Password Please");
if(password != 'password'){
document.body.innerHTML = '';
document.body.innerHTML = 'Password Failed! Reload to Renter Password';
}else{
alert('Success');
}
}
run();
</script>
</body>
</html>
