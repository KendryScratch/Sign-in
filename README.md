<!DOCTYPE html>

<html>
<head>
	<title>Sign in</title>
</head>
<body>

	<form action="file:///C:/Users/Administrator/Desktop/coding/html%20files/My%20Websites/First%20website/page1.html"  method="POST">

		<div>
		     <label for="fname"><b>First name:</b><label>
		     <input type="text"  id="fname"  name="fname" placeholder="Kendry"  requried>
		</div>

		<br>

		<div>
		     <label for="lname"><b>Last name:</b><label>
		     <input type="text"  id="lname"  name="lname" placeholder="Scratch"  requried>
		</div>

		<br>

		<div>
		     <label for="pass"><b>Password:</b><label>
		     <input type="password"  id="password"  name="password" maxlenght ="20" required>
		</div>

		<br>

		<div>
		     <label for="email"><b>Email:</b><label>
		     <input type="email"  id="email"  name="email" placeholder="kendryscratch@gmail.com" required>
		</div>

		<br>

		<div>
		     <label for="phone"><b>Phone#:</b><label>
		     <input type="tel"  id="phone"  name="phone" required>
		</div>

		<br>

		<div>
		     <label for="bdate"><b>Birthdate:</b><label>
		     <input type="date"  id="bdate"  name="bdate" required>
		</div>

		<br>


		<div>
		     <label><b>Gender: </b></label>&nbsp;

		     <label>Female</label>
		     <input type="radio" id="female" name="Female" value="Female">

		     <label>Male</label> 
		     <input type="radio" id="male" name="Male" value="Male">

		     <label>Non-binary</label>
		     <input type="radio" id="nonbinary" name="Non-binary" value="Non-binary" required>

			<br>

			<br>

			 <label for="age"><b>Age:</b></label>

			<select id="age">
			<ol>
			    <option value="Select">Select</option>
  			    <option value="Infant">Infant 0-1 year</option>
  			    <option value="Toddler">Toddler 2-4 years</option>
  			    <option value="Child">Child 5-12 years</option>
  			    <option value="Teenager">Teenager 13-19 years</option>
  			    <option value="Adult">Adult 20-39 years</option>
  			    <option value="Middle Age Adult">Middle Age Adult 40-59 years</option>
  			    <option value="Senior Adult">Senior Adult 60+</option>
			</ol>
			</select> 
		
		</div>
		
		<br>

		<div>
		     <input type="reset"> &nbsp; 
		     <input type="submit">
		
		</div>


		

		

	</form>
</body>
</html>
