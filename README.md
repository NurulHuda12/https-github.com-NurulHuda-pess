# https-github.com-Huda-pess
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<h1>Police Emergency Service System</h1>
<nav>
    <a href="logcall.php">Log Call</a>
    <a href="Update.php">Update</a>
    <a href="#">Report</a>
    <a href="#">History</a>
  </nav>
	<link href="pess_style.css" rel="stylesheet" type="text/css"/> 
</head>
<body>
<form name="frmLogCall" method="post"
	onSubmit="return validateForm()" action="dispatch.php">
<table>
  <tr>
     <td colspan="2">Log call Panel</td>
  </tr>
  
  <tr>
    <td>Caller's Name :</td>
    <td><input type="text" name="callerName" id="callerName"></td>
  </tr>
  <tr>
    <td>Contact No :</td>
    <td><input type="text" name="contactNo" id="contactNo"></td>
  </tr>
  <tr>
    <td>Location :</td>
    <td><input type="text" name="location" id="location"></td>
  </tr>
  <tr>
    <td>Incident Type :</td>
    <td>
      <select name="incidentType" id="incidentType"></select>
	  
    </td>
  </tr>
  <tr>
    <td>Description :</td>
    <td><textarea name="incidentDesc" id="incidentDesc" cols="45"
            rows="5"></textarea>
    </td>
  </tr>
  <tr>
    <td><input type="reset" name="btnCancel" id="btnCancel"
        value="Reset">
    </td>
    <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="submit"
        name="btnProcessCall" id="btnProcessCall" value="Process Call...">
    </td>
  </tr>
</table>
</form>
</body>
</html>
