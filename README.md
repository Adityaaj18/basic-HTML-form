# basic-HTML-form
simple html form
<!DOCTYPE html>
<html>
<head>
<title>basic HTML form</title>
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
</head>
<body>
	<h1 align="center">HTML Forms</h1>
	<table width="100%" bgcolor="blue" cellspacing="2" cellpadding="2">
		<tr align="center">
			<td><strong><font size="22" color="red">Student Entry</font></strong></td>
		</tr>
	</table>
	<h1>New Student Entry:</h1>
	<table width="100%" border="2" bordercolor="red" bgcolor="lightgreen" cellspacing="2" cellpadding="2">
	<tr>
	<td>
	<form name="student_entry" action="send.php" method="post">
	<table border="0" cellspacing="2" cellpadding="2">
		<tr>
			<td>Name:</td>
			<td><input type="text" maxlength="30"></td>
		</tr>
		
		<tr>
			<td>Roll no.:</td>
			<td><input type="text" maxlength="15"></td>
		</tr>
		
		<tr>
			<td>IEN no.:</td>
			<td><input type="text" maxlength="30"></td>
		</tr>
		
		<tr>
			<td>Official college email-id:</td>
			<td><input type="text" maxlength="30"></td>
		</tr>
		
		<tr>
			<td>Contact no.:</td>
			<td><input type="text" maxlength="30"></td>
		</tr>
		
		<tr>
			<td>Year & Department:</td>
			<td>
				<input type="radio" name="year">First year
				<input type="radio" name="year">Second year
				<input type="radio" name="year">Third year<br>
				
				<input type="radio" name="dep">Computer
				<input type="radio" name="dep">Mechanical
				<input type="radio" name="dep">Civil
				<input type="radio" name="dep">Electrical
				<input type="radio" name="dep">Chemical
			</td>
		</tr>
		
		<tr>
			<td>Comment / Complaint box:</td>
			<td>
				<textarea name="comm" cols="50" rows="10">
				</textarea>
			</td>
		</tr>
		
		<tr>
			<td></td>
			<td>
				<input type="Submit" name="Submit" value="Submit">
				<input type="Reset" name="Reset" value="Reset">
			</td>
		</tr>
	</table>
	</form>
	</td>
	</tr>
	</table>
</body>
</html>
