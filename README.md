

<!DOCTYPE html>
<html>
<head>
<title style="font-family:Magneto;">below-mendoza</title>
<script type="text/javascript" src="countryStateCity.js"></script>
</head>
<body>

<img src="http://previews.123rf.com/images/lenm/lenm1102/lenm110200305/8906158-Illustration-of-Girls-Exchanging-Books-Stock-Illustration-cartoon-books-exchange.jpg" alt="W3Schools.com" style="width:194px04px;height:142px;">
<style>h1 {
    text-align: leftwards;
}

h6 {
    
    text-align: leftwards;
	margin-left: 200px;
}
button { width: 6em }
button:hover
{
-moz-transform: rotate(360deg);
-webkit-transform: rotate(360deg);
-o-transform: rotate(360deg);
transform: rotate(360deg);

background:#99A411;
font-size:30px;
color:#fff;
}
button:before { width: 100px; content: ""; }
button:hover:before {content: "Reply!"}
}
</style>
<h1 style="color:maroon" style>Welcome to Books Barter Registration Page!</h1>
<h6><i>For those who love to read..</i></h6>
<form action="Register-user.php" method="POST">
<p>Enter your email address here: </p>
<input type="email" name=”Email” required="required" minlength="9" /> 
<p>Choose A Username: </p>
<input type="text" name="User" maxlength="15" size="10">
<br />
<p>Enter A Password: </p>
<input type="password" name="Password" minlength="8" size="10">
<p>Confirm Password: </p>
<input type="password" name="PasswordX2" size="10">
<br />
<p>Your location: </p>
<fieldset style="width: 230px;">
<legend><strong>Make your selection</strong></legend>
<select id="country" name="country"></select>
        <br />State:
        <select name="state" id="state"></select>
        <br/>
        <br />Select Country (without states):
        <select id="country2" name="country2"></select>
        <br />
        <script language="javascript">
            populateCountries("country", "state");
            populateCountries("country2");
        </script></select>
</td>
</tr><tr>
<td style="text-align: left;">City:</td>
<td style="text-align: left;">
<select name="city"  id="city">
  <option value="">Please select a Country</option>
  
</select>
</td>
</tr>

</table>
<p class="instructions-container">

  <label for="zip">Zip Code <span class="instructions">5 Digits</span></label>

  <input type="number" pattern="[0-9]*" maxlength="5" min="0" name="zip" id="zip">

</p>
</fieldset>
<button><span>click me</span></button>

<input type="submit" value="Sign up now">
<tr>
<td><a href="index.php">Sign In Here</a></td>
</tr>
</form>
<p id="demo"></p>

</body>
</html>
