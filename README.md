<!DOCTYPE html>
<html lang="en">
<head> <title>Form</title>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
    <h2>HTML Form</h2>
    
<form action="/action_page.php" method="post" autocomplete="on"  target="_blank">
    <label for="fname">Frist name:</label> <br>
    <input type="text" id="fname" name="fname" placeholder="Enter your frist name" required><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" placeholder="Enter your last name"  required><br>
    <label for="pass">password:</label><br>
    <input type="password" name="pass" id="pass" placeholder="Enter your password" minlength="8" maxlength="10" required><br>
    <label for="email">Email:</label><br>
    <input type="email" name="email" id="email" placeholder="Enter your email" required><br>
    <label for="phone">phone #:</label><br>
    <input type="tel" name="phone" id="phone" placeholder="(252)-12-3456789" required><br>
    <label for="bdate">Birthdate</label><br>
    <input type="date" id="bdate" name="bdate" required><br>
    <label for="quantity">Quantity</label><br>
    <input type="number" id="quantity" name="quantity" min="0" max="20" value="1"><br>
    <label for="payment">Payment</label><br>
    <select name="payment" id="payment" size="3" multiple><br>
        <option value="vasacard">Visacard</option>
        <option value="mastercard">Mastercard</option>
        <option value="giftcard">Giftcard</option>
        <option value="amazontcard">amazoncard</option>
        <option value="americantcard">americantcard</option>
    </select>

    <input type="submit" value="submit" required>
    <input type="reset">

</form>
    
<h2>Radio Buttons</h2>

<p>Choose your favorite Web language:</p>

<form >
    <input type="radio" id="html" name="Far_language">
    <label for="html">HTML</label><br>
    <input type="radio" name="Far_language" id="css" value="Css">
    <label for="css">CSS</label> <br>
    <input type="radio" name="Far_language" id="Javascript" value="Javascript">
    <label for="Javascript">Javascript</label><br>
    <button type="button" onclick="alert('This form is not working')">Click hear</button>
</form>

<h2>Checkboxes</h2>
<p>The <strong>input type="checkbox"</strong> defines a checkbox:</p>
<form action="/action_php" target="_blank">
    <fieldset style="width: 200px; height:200px;">
        <legend>Test Checkboxes</legend>
    <input type="checkbox" id="vihacle1" value="Bike">
    <label for="vihacle1">I have a bike</label><br>
    <input type="checkbox" id="vihacle2" value="Car">
    <label for="vihacle2"> I have a Car</label><br>
    <input type="checkbox" id="vihacle3" value="Boat">
    <label for="vihacle3"> I have a boat</label><br>
    <button type="button" onclick="alert('This form is not working')">Click hear</button>
    </fieldset>

<form action="/action_page.php">
        <input list="browsers" name="browser">
        <datalist id="browsers">
          <option value="Internet Explorer">
          <option value="Firefox">
          <option value="Chrome">
          <option value="Opera">
          <option value="Safari">
        </datalist>
        <button type="button" onclick="alert('This form is not working')">Click hear</button>
</form>


</form>

</body>
</html>
