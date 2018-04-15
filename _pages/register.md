---
ID: 173
post_title: Register
author: admin
post_excerpt: ""
layout: page
permalink: http://35.204.16.51/register/
published: true
post_date: 2018-04-15 15:20:06
---
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>

<section class="main-container">
<div>
Existing Users
			<div class="login-form">
				<form class="login-form" action="includes/login.inc.php" method="POST">
					<input type="text" name="uid" placeholder="username/e-mail">
					<input type="password" name="pwd" placeholder="password">
					<button type="submit" name="submit">Login</button>
				</form>
			</div>
Create Account
			<div class="signup-form">
		                 <form class="signup-form" action="includes/signup.inc.php" method="POST">
					<input type="text" name="first" placeholder="Firstname">
					<input type="text" name="last" placeholder="Lastname">
					<input type="text" name="email" placeholder="E-mail">
					<input type="text" name="uid" placeholder="Username">
					<input type="password" name="pwd" placeholder="Password">
					<button type="submit" name="submit">Register</button>
				</form>
			</div>
</section>

</body>
</html>