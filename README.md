# task-5
<html>
<head><title>Admission Application</title></head>
<body style="background-color: skyblue;">

<h1 style="background-color: #eOf2fe; color: #0369a1; text-align:center; padding: 15px; margin-top: 0;margin-bottom: 25px; border-radius: 6px; border: 1px solid #bae6fd;">STUDENT REGISTRATION FORM</h1>
<p>Create your account and join with us!</p>
<hr>

<form action="#" method="POST">

<h3 style="background-color: #800000 color: #ffffff; padding: 12px; margin-bottom: 25px; border radius: 4px;">1.Personal Information</h3>
<p>
<label for="fullname">Full Name :</label>
<input type="text" id="fullname" name="fullname">
</p>

<p>
<label for="email">Email Address :</label>
<input type="email" id="email" name="email">
</p>

<p>
<label for="mobile">Mobile Number :</label>
<input type="tel" id="mobile" name="mobile">
</p>

<p>
<label for="dob">Date of Birth :</label>
<input type="date" id="dob" name="dob">
</p>

<p>
<label>Gender :</label>
<input type="radio" id="male" name="gender" value="male">
<label for="male">Male</label>
<input type="radio" id="female" name="gender" value="female">
<label for="female">Female</label>
<input type="radio" id="other" name="gender" value="other">
<label for="other">Other</label>
</p>

<p>
<label for="address">Address :</label><br>
<textarea id="address" name="address" rows="4" cols="40"></textarea>
</p>

<hr>

<h3>2.Education Details</h3>
<p>
<label>Courser Interested In :</label>
<input type="checkbox" id="bsc" name="courses" value="bsc"><label for="bsc">BSC</label>
<input type="checkbox" id="bca" name="courses" value="bca"><label for="bca">BCA</label>
<input type="checkbox" id="bcom" name="courses" value="bcom"><label for="bcom">BCOM</label>
<input type="checkbox" id="bba" name="courses" value="bba"><label for="bba">BBA</label>
</p>

<p>
<label>Year of Study :</label>
<input type="radio" id="1st" name="year" value="1"><label for="1st">1st Year</label>
<input type="radio" id="2nd" name="year" value="2"><label for="2nd">2nd Year</label>
<input type="radio" id="3rd" name="year" value="3"><label for="3rd">3rd Year</label>
</p>

<p>
<label for="dept">Department :</label>
<select id="dept" name="department">
<option value="">--Select Department--</option>
<option value="cs">Computer Science</option>
<option value="commerce">Commerce</option>
<option value="mgmt">Management</option>
</select>
</p>

<hr>

<h3>3.Account Information</h3>
<p>
<label for="username">Username :</label>
<input type="text" id="username" name="username">
</p>

<p>
<label for="password">Password :</label>
<input type="password" id="password" name="password">
</p>

<p>
<label for="confirm_pass">Confirm Password :</label>
<input type="password" id="confirm_pass" name="confirm_pass">
</p>

<hr>

<h3>4.Upload & Other Details</h3>
<p>
<label for="photo">Upload Photo :</label>
<input type="file" id="photo" name="photo">
</p>

<p>
<label for="source">How did you know about us? :</label>
<select id="source" neam="source">
<option value="">--Select Option--</option>
<option value="internet">Internet</option>
<option value="friend">Friend</option>
<option value="ad">Advertisement</option>
</select>
</p>


<p>
<input type="submit" value="Submit Registration">
<input type="reset" value="Reset Form">
<input type="button" value="Custom Button">
</p>
</form>

<p>Already have an account? <a href="#">Click here to login</a></p>
</body>
</html>
